cmake_minimum_required(VERSION 3.0)

project(caps+ctrl2esc)

add_executable(caps+ctrl2esc caps+ctrl2esc.c)
target_compile_options(caps+ctrl2esc PRIVATE -Wall -Wextra)

install(TARGETS caps+ctrl2esc RUNTIME DESTINATION bin)
