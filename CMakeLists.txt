project(stb)

add_library(stb STATIC stb.cc)

target_include_directories(stb PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
