cmake_minimum_required(VERSION 3.14...3.27)

if(${CMAKE_VERSION} VERSION_LESS 3.12)
    cmake_policy(VERSION ${CMAKE_MAJOR_VERSION}.${CMAKE_MINOR_VERSION})
endif()

set(This Tests)
set(Sources ExampleTest.cpp)

add_executable(${This} ${Sources})