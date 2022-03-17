cmake_minimum_required(VERSION 3.14)
PROJECT(5)

set(CMAKE_CXX_STANDARD 17)


ADD_EXECUTABLE(5-1 5-1byteorder.cpp)
ADD_EXECUTABLE(5-3 5-3testlisten.cpp)
ADD_EXECUTABLE(5-5testaccept.cpp 5-5testaccept.cpp)
ADD_EXECUTABLE(5-6oobsend.cpp 5-6oobsend.cpp)
ADD_EXECUTABLE(5-7oobrecv.cpp 5-7oobrecv.cpp)
ADD_EXECUTABLE(5-12access_daytime.cpp 5-12access_daytime.cpp)