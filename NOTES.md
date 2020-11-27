Baud rate 115200
#define BAUDRATE 115200

Turn on bed temp sensor
#define TEMP_SENSOR_BED 1

To enable LCD, ensure uncommented:
#define REPRAP_DISCOUNT_SMART_CONTROLLER

To enable BLTOUCH probe, ensure uncommented:
#define BLTOUCH

Z-axis lead screws have different pitch than original, set:
#define DEFAULT_AXIS_STEPS_PER_UNIT   { 80, 80, 400, 400 }

For direct drive extruder, set
#define INVERT_E0_DIR true

I put the Y endstop on the other side, set these
#define Y_HOME_DIR 1
#define Y_MIN_ENDSTOP_INVERTING true // Set to true to invert the logic of the endstop.
#define Y_MAX_ENDSTOP_INVERTING true // Set to true to invert the logic of the endstop.
//#define USE_YMIN_PLUG
#define USE_YMAX_PLUG
