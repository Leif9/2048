cmake_minimum_required(VERSION 3.21)
project(2048)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)

add_executable(2048
        .idea/2048.iml
        .idea/modules.xml
        .idea/vcs.xml
        .idea/workspace.xml
        main.c
        README.md)
