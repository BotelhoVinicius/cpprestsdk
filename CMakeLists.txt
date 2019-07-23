cmake_minimum_required(VERSION 2.8)
project(cpprestsdk-root NONE)

#if(CMAKE_CXX_COMPILER_VERSION VERSION_LESS 4.8)
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fpermissive")
#endif()

add_subdirectory(Release)
