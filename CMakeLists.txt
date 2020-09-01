cmake_minimum_required(VERSION 3.10)

PROJECT(TSP)
file( GLOB SRC_LIST ${PROJECT_SOURCE_DIR}/*.cpp)
#message( STATUS "SRC_LIST is" ${SRC_LIST}  )
ADD_EXECUTABLE(tsp ${SRC_LIST})

