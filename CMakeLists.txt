cmake_minimum_required(VERSION 3.10)

# Set the project name
project(LinearAlgebra)

# Add the executable
add_executable(linearalgebra src/main.c src/functions.c)

# Or, you can use a wildcard to include all C files in the src directory
# file(GLOB SOURCES "src/*.c")
# add_executable(MyExecutable ${SOURCES})
