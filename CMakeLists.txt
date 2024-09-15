cmake_minimum_required(VERSION 3.2)

project( LitLua )

set_property(GLOBAL PROPERTY USE_FOLDERS ON)

add_subdirectory(deps/lua)
add_subdirectory(src)
