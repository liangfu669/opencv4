cmake_minimum_required(VERSION 3.23)
project(opencv4)

set(CMAKE_CXX_STANDARD 14)
set(OpenCV_DIR C:/Users/86199/opencv/build)
find_package(OpenCV REQUIRED)

add_executable(main main.cpp)
target_link_libraries(main ${OpenCV_LIBS})

add_subdirectory(chapter2)
