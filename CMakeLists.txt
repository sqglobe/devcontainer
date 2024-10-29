cmake_minimum_required(VERSION 3.5)

project(app LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(app main.cpp)

install(TARGETS app
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
