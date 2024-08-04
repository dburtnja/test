
add_library(test_shared_lib SHARED shared.cpp)
target_include_directories(test_shared_lib PUBLIC .)
