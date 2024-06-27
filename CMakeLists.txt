cmake_minimum_required(VERSION 3.28)
project(TSP)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(data_structures)

add_executable(TSP
        src/Graph.cpp
        src/Graph.h
        src/MutablePriorityQueue.h
        src/ParsingFunctions.cpp
        src/ParsingFunctions.h
        src/main.cpp
        src/App.cpp
        src/App.h
        src/BackTracking.cpp
        src/BackTracking.h
        src/TriangularApproximation.cpp
        src/TriangularApproximation.h
        src/OtherHeuristics.cpp
        src/OtherHeuristics.h
        src/RealWorld.cpp
        src/RealWorld.h
)