cmake_minimum_required(VERSION 3.16)
project(JobUart
    VERSION 0.0.1
    LANGUAGES CXX
)


add_subdirectory(libs)

# add_subdirectory(apps)

enable_testing()
add_subdirectory(tests)
