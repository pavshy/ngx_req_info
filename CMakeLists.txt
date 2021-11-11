cmake_minimum_required(VERSION 3.20)
project(ngx_req_info C)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c library.c)

add_library(ngx_req_info library.c)

add_executable(run ${SOURCE_FILES})
