cmake_minimum_required(VERSION 3.5)

set(CMAKE_C_EXTENSIONS OFF)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)

project("project")

include_directories("include")

add_executable("project"
"src/project/main.cpp"
"src/project/project.cpp"
)
