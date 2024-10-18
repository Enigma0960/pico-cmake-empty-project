add_executable(target main.cpp)

target_include_directories(target PUBLIC ${CMAKE_CURRENT_LIST_DIR})

target_link_libraries(target pico_stdlib pico_stdio)

pico_add_extra_outputs(target)