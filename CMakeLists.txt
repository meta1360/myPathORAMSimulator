cmake_minimum_required(VERSION 3.10)
project(myPathORAMSimulator)

set(CMAKE_CXX_STANDARD 11)

add_executable(myPathORAMSimulator BinPathORam.cpp BinPathORam.h SimpleCache.cpp SimpleCache.h Parameters_ORAM.h BinPathORam_test.cpp HierBinPathORam.cpp HierBinPathORam.h UnifiedBinPathORam.cpp UnifiedBinPathORam.h)