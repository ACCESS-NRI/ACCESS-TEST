cmake_minimum_required(VERSION 3.1)

project(my_project DESCRIPTION "Stub test program"
        LANGUAGES Fortran)
enable_language(Fortran)
find_package(MPI REQUIRED)

# Source code
add_executable(hello_world.exe src/hello_world.f90)

install(TARGETS hello_world.exe     DESTINATION "bin")
