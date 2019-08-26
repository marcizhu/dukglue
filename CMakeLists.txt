cmake_minimum_required(VERSION 3.1)

add_library(dukglue INTERFACE)
target_include_directories(dukglue SYSTEM INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
target_compile_definitions(dukglue INTERFACE _CRT_SECURE_NO_WARNINGS)