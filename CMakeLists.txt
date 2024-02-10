cmake_minimum_required(VERSION 3.5.1)

project(rayminapp)

add_executable( rayminapp
                rayminapp.cpp
)

target_link_libraries( rayminapp raylib )

