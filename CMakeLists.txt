cmake_minimum_required(VERSION 3.28)
project(c_mapreduce C)

set(CMAKE_C_STANDARD 11)

add_executable(c_mapreduce main.c
        mapreduce.c)
