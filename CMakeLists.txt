cmake_minimum_required(VERSION 3.21)
project(Project_Raycaster)

set(CMAKE_CXX_STANDARD 14)

add_executable(Project_Raycaster main.cpp)
target_link_libraries(Project_Raycaster -lOpenGL32 -glu32 -lfreeGLUT -lglu32)