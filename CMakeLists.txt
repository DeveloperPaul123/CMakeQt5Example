
project(GettingStartedWithCmake)
cmake_minimum_required(VERSION 3.0.0 FATAL_ERROR)

# find Qt5 and required components
find_package(Qt5 COMPONENTS REQUIRED Core Gui Widgets)

set(project_sources 
	mainwindow.cpp)

set(project_headers
	mainwindow.h)

set(project_ui
	mainwindow.ui)

