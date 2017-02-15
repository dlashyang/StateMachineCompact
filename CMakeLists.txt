cmake_minimum_required(VERSION 2.8.4)

PROJECT(StateMachineCompact)

add_definitions(
    -g
    -Wall
    )

include_directories(
    ./
    )

aux_source_directory(. src_list)
add_executable(moto ${src_list})

#find_library(poco_f PocoFoundation /usr/local)
#target_link_libraries(rpswd )
