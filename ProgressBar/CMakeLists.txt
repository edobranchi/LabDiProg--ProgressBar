cmake_minimum_required(VERSION 3.8)
project(ProgressBar)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Objects/MingW/lolol_private.h
        Objects/MingW/lolol_private.rc
        Objects/MingW/lolol_private.res
        "Objects/MingW/progress barApp.o"
        "Objects/MingW/progress barFrm.o"
        Objects/MingW/ProgressBar_private.h
        Objects/MingW/ProgressBar_private.rc
        Objects/MingW/ProgressBar_private.res
        Makefile.win)

add_executable(ProgressBar ${SOURCE_FILES})