# TODO: find out which version is actually required
cmake_minimum_required(VERSION 3.1)

project(synfig)

enable_testing()

# using latest stable standard, but not strictly
# the rest is done via target_compile_features instead
set(CMAKE_CXX_STANDARD 14)

add_subdirectory(src)
