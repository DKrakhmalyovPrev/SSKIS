cmake_minimum_required(VERSION 2.6)

enable_language(CXX)
set(CMAKE_CXX_STANDARD 11)
project(main)
# Include
include_directories(A)
#add_dependencies(SSKIS/A/index.h SSKIS/B/main.h)
# Link 
add_executable(main B/main.cpp)

