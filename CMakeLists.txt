cmake_minimum_required(VERSION 3.8)
project(sireye_http_tinyHttp)
find_package(Threads)
set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp )
add_executable(tinyHttp ${SOURCE_FILES})
target_link_libraries(sireye_http_tinyHttp ${CMAKE_THREAD_LIBS_INIT})
