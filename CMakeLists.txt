#Cmake build file

CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
PROJECT(belirium-init)
add_definitions(-O2)
file(GLOB C_SRCS src/*.c)
add_executable(belirium-init ${C_SRCS})