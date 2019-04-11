Cmake_minimum_required (VERSION 3.11)
project (sourceSDK)

option(sourceSDK_Build_MP "Build Multiplayer" OFF )

if(${sourceSDK_Build_MP})
  include(${CMAKE_CURRENT_SOURCE_DIR}/mp)
else
  include(${CMAKE_CURRENT_SOURCE_DIR}/sp)
endif(${sourceSDK_Build_MP})