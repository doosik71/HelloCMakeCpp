cmake_minimum_required(VERSION 3.17)

project(HelloCMakeCpp LANGUAGES CXX)

add_executable(HelloCMakeCpp)

target_sources(HelloCMakeCpp PRIVATE
	${CMAKE_SOURCE_DIR}/src/HelloCMakeCpp.cpp
)
