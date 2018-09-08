#add_library(half INTERFACE)
#target_include_directories(half INTERFACE include/)
#install(TARGETS half INCLUDES DESTINATION include)
INSTALL(DIRECTORY ${CMAKE_CURRENT_LIST_DIR}/include/ DESTINATION ${CMAKE_INSTALL_PREFIX}/include)