cmake_minimum_required(VERSION 3.9)
project(T2_ORI)

set(CMAKE_CXX_STANDARD 11)

add_executable(T2_ORI main.cpp BTreeNode.cpp GerenciadorDeBlocos.cpp  BTree.cpp )
