cmake_minimum_required (VERSION 2.8) 

#SET(CMAKE_C_COMPILER C:/MinGW/msys/mingw/bin/gcc.exe)
SET(CMAKE_CXX_COMPILER C:/MinGW/msys/mingw/bin/g++.exe)

project (Test)

ADD_EXECUTABLE (testrst test.cpp)

#SET(CMAKE_CXX_CPPCHECK "C:/Program Files/Cppcheck/cppcheck.exe")
#SET(CXX_CPPCHECK test2.out)
#add_RunCMake_test(Cppcheck -DPSEUDO_CPPCHECK=$<TARGET_FILE:test2.out>)
