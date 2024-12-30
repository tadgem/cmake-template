CMAKE_MINIMUM_REQUIRED(VERSION 3.12)

project(project_name)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(library_name)
add_subdirectory(tests)

# Any executables can be added as needed
# add_subdirectory(app_template)