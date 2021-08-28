cmake_minimum_required(VERSION 3.16)

add_subdirectory(cppcodec)
add_executable(pr_fix src/main.cpp)
target_link_libraries(cppcodec)

