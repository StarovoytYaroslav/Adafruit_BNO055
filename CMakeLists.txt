idf_component_register(
    SRCS "Adafruit_BNO055.cpp"
    INCLUDE_DIRS "."
    REQUIRES arduino-esp32 Adafruit_BusIO Adafruit_Sensor
)
