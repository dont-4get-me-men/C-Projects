cmake_minimum_required(VERSION 3.13)
project(DVector_DMatrix__Ryzhkin C)

set(CMAKE_C_STANDARD 99)

add_executable(DVector_DMatrix__Ryzhkin Dmatrix_tests.c src/Dmatrix.c src/Dmatrix.h)
