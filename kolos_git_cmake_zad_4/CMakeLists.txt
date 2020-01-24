cmake_minimum_required(VERSION 2.8.9)
project(kolos)
 
#Dolacza pliki naglowkowe
include_directories(include)
 

#Dolacza pliki zrodlowe
file(GLOB SOURCES "src/*.cpp")
 
add_executable(myProgram ${SOURCES})

