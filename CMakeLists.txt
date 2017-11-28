cmake_minimum_required(VERSION 3.6)

create_static_library(
    TARGET
        nanopb
    SOURCES
        pb_common.c
        pb_decode.c
        pb_encode.c
    INCLUDE_DIRS
        .
)
