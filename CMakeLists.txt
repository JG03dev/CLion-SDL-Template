cmake_minimum_required(VERSION 3.25)
project(SDL_CLION_template)

set(CMAKE_CXX_STANDARD 17)

add_executable(SDL_CLION_template main.cpp)

# Link SDL2 library
target_link_libraries(SDL_CLION_template SDL2)