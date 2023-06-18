cmake_minimum_required(VERSION 3.5)
project(DIPolicies VERSION 0.1 DESCRIPTION "DIPolicies module" LANGUAGES CXX)

file( GLOB SOURCES **.cpp )

SetFlags()
SetLibraries( )
CreateLibrary( ${PROJECT_NAME} )