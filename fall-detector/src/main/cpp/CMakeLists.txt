cmake_minimum_required(VERSION 3.4.1)

add_library(detector SHARED
            detector.c)

# Include libraries needed for detector lib
target_link_libraries(detector
                      android
                      log)