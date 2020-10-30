cmake_minimum_required(VERSION 3.17)
project(bass_ffmpeg)

set(CMAKE_CXX_STANDARD 17)

add_library(bass_ffmpeg SHARED library.cpp library.hpp)