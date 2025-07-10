# CMakeFiles.txt inside "SparkFun_BNO08x_Arduino_Library" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/SparkFun_BNO08x_Arduino_Library.cpp" "src/sh2_SensorValue.c" "src/sh2_util.c" "src/sh2.c" "src/shtp.c"
                    INCLUDE_DIRS "." "src/."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(SparkFun_BNO08x_Arduino_Library)