# CMakeList.txt : CMake project for imgui-sample1, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("imgui-sample1" )
set(CMAKE_TOOLCHAIN_FILE "C:/tools/vcpkg/scripts/buildsystems/vcpkg.cmake")
# Add source to this project's executable.
add_executable (imgui-sample1 "imgui-sample1.cpp" "imgui-sample1.h")

# "-=C:/tools/vcpkg/scripts/buildsystems/vcpkg.cmake"

# TODO: Add tests and install targets if needed.
