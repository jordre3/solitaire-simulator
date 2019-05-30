cmake_minimum_required(VERSION 3.14)
project(projectFiles)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(projectFiles
        Card.cpp
        Card.h
        Deck.cpp
        Deck.h
        GameBoard.cpp
        Gameboard.h
        Solitaire.cpp
        Solitaire.h)
