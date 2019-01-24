cmake_minimum_required(VERSION 3.1.3)

project(AudioFile CXX)
set(CMAKE_CXX_STANDARD 11) #supported from cmake 3.1

SET(AudioFile_SOURCE
        AudioFile.h
        AudioFile.cpp
        )

add_library(audiofile ${AudioFile_SOURCE})