cmake_minimum_required(VERSION 3.14)
project(GameEngine)

# Makes sure the standard C++20 is used on both g++ and cl.exe
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# Compiles main.cpp into an executable called main
add_executable(main src/main.cpp)