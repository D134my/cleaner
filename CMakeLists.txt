cmake_minimum_required(VERSION 3.5)

project(cleaner LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(cleaner main.cpp types.hpp clean.hpp clean.cpp )
target_link_libraries(cleaner stdc++fs)
