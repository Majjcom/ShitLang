cmake_minimum_required(VERSION 3.16.0)

project(lua)

aux_source_directory(src SRC_LIB)

add_library(lua_lib OBJECT ${SRC_LIB})

aux_source_directory(src/lua SRC_LUA)
aux_source_directory(src/luac SRC_LUAC)

add_executable(lua ${SRC_LUA})
add_executable(luac ${SRC_LUAC})

target_link_libraries(lua lua_lib)
target_link_libraries(luac lua_lib)
