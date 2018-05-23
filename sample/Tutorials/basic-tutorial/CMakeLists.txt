cmake_minimum_required(VERSION 3.9)
 
PROJECT(gstreamer_basic_tutorial)
 
INCLUDE_DIRECTORIES("D:/gstreamer/1.0/x86_64/include")
INCLUDE_DIRECTORIES("D:/gstreamer/1.0/x86_64/include/gstreamer-1.0")
INCLUDE_DIRECTORIES("D:/gstreamer/1.0/x86_64/include/glib-2.0")
INCLUDE_DIRECTORIES("D:/gstreamer/1.0/x86_64/lib/glib-2.0/include")

LINK_DIRECTORIES("D:/gstreamer/1.0/x86_64/lib")
 
ADD_SUBDIRECTORY(basic-tutorial-1)
ADD_SUBDIRECTORY(basic-tutorial-2)
ADD_SUBDIRECTORY(basic-tutorial-3)
ADD_SUBDIRECTORY(basic-tutorial-4)
ADD_SUBDIRECTORY(basic-tutorial-5)
ADD_SUBDIRECTORY(basic-tutorial-6)
ADD_SUBDIRECTORY(basic-tutorial-7)
ADD_SUBDIRECTORY(basic-tutorial-8)
ADD_SUBDIRECTORY(basic-tutorial-9)
ADD_SUBDIRECTORY(basic-tutorial-12)
ADD_SUBDIRECTORY(basic-tutorial-13)
ADD_SUBDIRECTORY(basic-tutorial-15)