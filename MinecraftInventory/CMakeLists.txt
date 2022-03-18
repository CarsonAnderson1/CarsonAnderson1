cmake_minimum_required(VERSION 3.21)
project(MinecraftInventory)

set(CMAKE_CXX_STANDARD 14)

add_executable(MinecraftInventory main.cpp Inventory.cpp Inventory.h Item.cpp Item.h)
