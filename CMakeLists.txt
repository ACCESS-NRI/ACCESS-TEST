cmake_minimum_required(VERSION 3.1)

project(my_project DESCRIPTION "Stub test program"
        LANGUAGES Fortran)
enable_language(Fortran)

# Source code
add_subdirectory(src)

install(TARGETS stub.ee     DESTINATION "bin")
