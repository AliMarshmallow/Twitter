cmake_minimum_required(VERSION 3.17)
project(project C)

set(CMAKE_C_STANDARD 11)

add_executable(project main.c cJSON.c)
target_link_libraries(project ws2_32)

