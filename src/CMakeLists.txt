cmake_minimum_required(VERSION 3.2)

project( LuaBrige )

set(LUA_BRIGE_SOURCES "main.cpp")

source_group("src" FILES ${LUA_BRIGE_SOURCES})

add_executable(LuaBrige ${LUA_BRIGE_SOURCES})

target_link_directories(LuaBrige PUBLIC LuaLib)
