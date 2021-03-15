cmake_minimum_required(VERSION 3.1)
project(Kinect-Azure-Captured-System)

add_executable(Kinect-Azure-Captured-System Source.cpp transform_main.cpp transformation_helpers.cpp)
target_link_libraries(Kinect-Azure-Captured-System PRIVATE k4a ${OpenCV_LIBS})
