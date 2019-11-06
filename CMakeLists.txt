cmake_minimum_required(VERSION 3.15)
project(libuv_work C)

set(CMAKE_C_STANDARD 99)

add_executable(libuv_work main.c)
target_link_libraries(libuv_work uv)