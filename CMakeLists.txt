project(test_app C)
cmake_minimum_required(VERSION 3.1.6)

add_executable (app app.c)

install(TARGETS app DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

