cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

include(sources_functions)

set(TARGET "ImageSteganography")

add_executable("${TARGET}")

assign_sources_to_target(TARGET ${TARGET})
