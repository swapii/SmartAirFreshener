set(PROJECT_NAME freshner)
project(${PROJECT_NAME} C CXX)
set(${PROJECT_NAME}_SRCS freshener.cpp)
set(freshner_SERIAL screen @SERIAL_PORT@ 9600)
generate_arduino_firmware(${PROJECT_NAME})
