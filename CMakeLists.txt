cmake_minimum_required(VERSION 3.8)
project(opencvProj)
find_package(OpenCV REQUIRED)
add_executable(mainRun main.cpp)
target_link_libraries(mainRun ${OpenCV_LIBS})
