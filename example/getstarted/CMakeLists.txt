project(example)
include_directories(../../src/)
add_executable(example main.cpp)
target_link_libraries(example cpp-elasticsearch)
