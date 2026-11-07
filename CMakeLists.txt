cmake_minimum_required(VERSION 4.4)
project(audio_spore)

set(CMAKE_CXX_STANDARD 23)

add_library(audio_spore STATIC src/library.cpp)
