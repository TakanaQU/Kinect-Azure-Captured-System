project(Kinect-Azure-Captured-System)

# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License.
add_executable(Kinect-Azure-Captured-System Source.cpp transform_main.cpp transformation_helpers.cpp)
target_link_libraries(Kinect-Azure-Captured-System PRIVATE k4a ${OpenCV_LIBS})
