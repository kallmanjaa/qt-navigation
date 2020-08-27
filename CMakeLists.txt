CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

## set prefix and sysroot
SET(CMAKE_PREFIX_PATH ${PREFIX_PATH})
SET(CMAKE_SYSROOT ${SYSROOT})

## strip the executbale
SET(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -s")
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -s")

## add other apps test cases etc
ADD_SUBDIRECTORY(apps)

