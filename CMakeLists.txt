cmake_minimum_required(VERSION 2.8)

project(waifu2x-experiment)

set(WITH_IPP OFF CACHE BOOL "Include Intel IPP support")
add_subdirectory(opencv)

#add_subdirectory(caffe)
