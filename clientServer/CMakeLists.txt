cmake_minimum_required(VERSION 3.2)

project(clientServer)
add_executable(${PROJECT_NAME} "main.cpp" "server.cpp")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread -lncurses")