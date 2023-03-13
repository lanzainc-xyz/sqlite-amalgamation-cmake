cmake_minimum_required(VERSION 3.2)
project(sqlite)

# sqlite
add_library(sqlite STATIC ./sqlite3.c)
target_include_directories(sqlite PUBLIC ./)
