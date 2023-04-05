cmake_minimum_required(VERSION 2.8)
project(trim)
add_executable(${PROJECT_NAME}.exe main.cpp)
install(TARGETS ${PROJECT_NAME}.exe DESTINATION bin)
