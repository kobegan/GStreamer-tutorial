

SET(GSTREAMER_BASIC_TUTORIAL basic-tutorial-15.c)

add_executable(basic-tutorial-15 ${GSTREAMER_BASIC_TUTORIAL})

target_link_libraries(basic-tutorial-15 gobject-2.0 glib-2.0 gstreamer-1.0 gstbase-1.0)