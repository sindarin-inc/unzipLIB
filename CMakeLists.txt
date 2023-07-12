cmake_minimum_required(VERSION 3.5)

idf_component_register(
     SRCS src/unzip.c src/unzipLIB.cpp
     INCLUDE_DIRS "src"
     REQUIRES zlib
)

project(unzipLIB)
