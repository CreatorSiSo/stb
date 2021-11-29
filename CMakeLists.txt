cmake_minimum_required(VERSION 3.0)

project(stb_image)

# Targets
add_library(
  ${PROJECT_NAME} STATIC ./stb_image.cpp)

# Includes
target_include_directories(${PROJECT_NAME} PUBLIC ./ )
