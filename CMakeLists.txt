
add_library(test_shared_lib SHARED shared.cpp)
target_include_directories(test_shared_lib PUBLIC .)

install(TARGETS test_shared_lib
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    PUBLIC_HEADER DESTINATION ${CMAKE_INSTALL_INCLUDEDIR})
