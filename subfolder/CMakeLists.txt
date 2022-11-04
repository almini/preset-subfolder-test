cmake_minimum_required(VERSION 3.16)
project(clion_preset_subfolder_test)

add_subdirectory(.. ${CMAKE_CURRENT_BINARY_DIR}/root)

add_executable(clion_preset_subfolder_test main.cpp)