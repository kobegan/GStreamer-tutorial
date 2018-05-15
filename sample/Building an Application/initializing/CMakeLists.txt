

SET(INITIALIZING main.cpp)

add_executable(initializing ${INITIALIZING})

target_link_libraries(initializing gobject-2.0 glib-2.0 gstreamer-1.0 gstbase-1.0)