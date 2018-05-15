cmake_minimum_required(VERSION 3.9)
 
PROJECT(BuildApplication)
 
INCLUDE_DIRECTORIES("H:/gstreamer/1.0/x86_64/include")
INCLUDE_DIRECTORIES("H:/gstreamer/1.0/x86_64/include/gstreamer-1.0")
INCLUDE_DIRECTORIES("H:/gstreamer/1.0/x86_64/include/glib-2.0")
INCLUDE_DIRECTORIES("H:/gstreamer/1.0/x86_64/lib/glib-2.0/include")

LINK_DIRECTORIES("H:/gstreamer/1.0/x86_64/lib")
 
ADD_SUBDIRECTORY(initializing)
#ADD_SUBDIRECTORY(stop_or_terminate_thread)
#ADD_SUBDIRECTORY(lambda)
#ADD_SUBDIRECTORY(smart_pointer)
#ADD_SUBDIRECTORY(std_array)
#ADD_SUBDIRECTORY(variadic_templates)
#ADD_SUBDIRECTORY(rvalue_reference)
#ADD_SUBDIRECTORY(callbacks)
