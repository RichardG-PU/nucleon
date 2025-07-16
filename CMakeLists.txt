cmake_minimum_required(VERSION 3.16)
project(Nucleon)

set(CMAKE_CXX_STANDARD 20)

include_directories(include)
file(GLOB_RECURSE SOURCES src/*.cpp)

add_executable(myon ${SOURCES})

find_package(OpenGL REQUIRED)
target_link_libraries(myon PRIVATE glfw OpenGL::GL)

