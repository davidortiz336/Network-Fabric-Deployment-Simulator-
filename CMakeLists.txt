cmake_minimum_required(VERSION 3.10)
project(NetworkFabricSimulator)

set(CMAKE_CXX_STANDARD 17)

# Source files
file(GLOB SRC_FILES src/*.cpp)

add_executable(fabric ${SRC_FILES})

target_include_directories(fabric PUBLIC include)