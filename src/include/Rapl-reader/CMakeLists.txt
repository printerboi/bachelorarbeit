cmake_minimum_required(VERSION 3.16)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(rapl_reader
        RegisterReader.cpp RegisterReader.h)
