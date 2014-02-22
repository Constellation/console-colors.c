cmake_minimum_required(VERSION 2.8)

project(console-colors C)
enable_testing()

add_library(console-colors STATIC console-colors.c)
add_executable(example
    test/example.c
    )
target_link_libraries(example console-colors)
add_test(test example)
