cmake_minimum_required(VERSION 3.15)
project(cpp-my-rest-app)

add_executable(cpp-my-rest-app main.cpp)
target_include_directories(cpp-my-rest-app PRIVATE cpp-my-rest-libs)
target_link_libraries(cpp-my-rest-app cpp-my-rest-libs)
