cmake_minimum_required(VERSION 3.12)
project(project)

set(CMAKE_CXX_STANDARD                  17)
set(CMAKE_CXX_STANDARD_REQUIRED         17)
set(CMAKE_CXX_EXTENSIONS               OFF)

# Export comiple comands for YCM
set(CMAKE_EXPORT_COMPILE_COMMANDS       ON)


# Add executable
add_executable(main main.cc)
