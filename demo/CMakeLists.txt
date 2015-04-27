cmake_minimum_required(VERSION 2.8)

# Build a simple C program.
add_executable(hello "hello.c")

# Add simple test suite.
enable_testing()
add_test(test-hello "${CMAKE_CURRENT_BINARY_DIR}/hello")
