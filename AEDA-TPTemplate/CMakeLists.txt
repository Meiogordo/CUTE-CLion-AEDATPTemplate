cmake_minimum_required(VERSION 3.8)
project(AEDA_TPTemplate)

set(CMAKE_CXX_STANDARD 11)

include_directories(cute_lib)
file(GLOB_RECURSE SOURCE_FILES "src/*.cpp")
add_executable(AEDA_TPTemplate ${SOURCE_FILES})