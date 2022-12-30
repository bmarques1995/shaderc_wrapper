cmake_minimum_required(VERSION 3.20)
project(shaderc_wrapper)

message(${CMAKE_INSTALL_PREFIX})

add_subdirectory(./vendor/spirv-headers)
add_subdirectory(./vendor/spirv-tools)
add_subdirectory(./vendor/googletest)
add_subdirectory(./vendor/re2)
add_subdirectory(./vendor/effcee)
add_subdirectory(./vendor/glslang)
add_subdirectory(./vendor/shaderc)