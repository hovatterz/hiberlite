cmake_minimum_required(VERSION 2.8)

project(hiberlite)

include_directories("include")

add_library(hiberlite
    src/BeanLoader.cpp
    src/BeanUpdater.cpp
    src/ChildKiller.cpp
    src/CppModel.cpp
    src/Database.cpp
    src/ModelExtractor.cpp
    src/Registry.cpp
    src/SQLiteStmt.cpp
    src/Visitor.cpp
    src/shared_res.cpp)
