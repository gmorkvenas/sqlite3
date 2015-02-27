cmake_minimum_required(VERSION 2.6)

project(sqlite3 C)

set(src_dir ${CMAKE_CURRENT_SOURCE_DIR}/src)
file(GLOB_RECURSE src_files ${src_dir}/*)
add_library(sqlite3 STATIC ${src_files})
