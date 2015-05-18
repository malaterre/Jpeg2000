cmake_minimum_required(VERSION 3.0)
project(BarBarJP2)
#target_compile_features(barbar PRIVATE cxx_range_for)
add_definitions(-std=c++11)
add_executable(barbar main.cpp
common.cpp
j2k.cpp
j2p.cpp
)
