cmake_minimum_required(VERSION 3.10)
project(3dEngine)

find_package(SDL2 REQUIRED)

add_executable(3dEngine ../test.cpp)

target_link_libraries(3dEngine SDL2::SDL2 SDL2::SDL2main)
