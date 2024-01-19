cmake_minimum_required(VERSION 3.6 FATAL_ERROR)

project(
    VulkanMemoryAllocator-Hpp
    VERSION 0
    DESCRIPTION "C++ bindings for the VulkanMemoryAllocator library."
    LANGUAGES C CXX)

add_library(VulkanMemoryAllocator-Hpp INTERFACE)

target_include_directories(VulkanMemoryAllocator-Hpp INTERFACE $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>)
