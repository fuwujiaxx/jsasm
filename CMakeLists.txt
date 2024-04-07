cmake_minimum_required(VERSION 3.24...3.25)

aux_source_directory(. SRCS)

add_executable(jsasm)

target_sources(jsasm PRIVATE ${SRCS})
