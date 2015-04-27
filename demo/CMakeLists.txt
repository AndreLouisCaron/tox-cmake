cmake_minimum_required(VERSION 2.8)

get_filename_component(
  CMAKE_PATH
  "[HKEY_LOCAL_MACHINE\\SOFTWARE\\Kitware\\CMake 2.8.10.1]"
  ABSOLUTE CACHE
)

message(STATUS "CMAKE_PATH: \"${CMAKE_PATH}\".")
