# CMake build : library

#configure variables
set (LIB_NAME "${PROJECT_NAME}Lib")

#configure directories
set (LIBRARY_MODULE_PATH "${PROJECT_SOURCE_DIR}/lib")
set (LIBRARY_SRC_PATH "${LIBRARY_MODULE_PATH}/src")
set (LIBRARY_INCLUDE_PATH "${LIBRARY_MODULE_PATH}/include")

#set includes
include_directories (${LIBRARY_INCLUDE_PATH})

#set sources
file (GLOB LIB_HEADER_FILES "${LIBRARY_INCLUDE_PATH}/*.h")
file (GLOB LIB_SOURCE_FILES "${LIBRARY_SRC_PATH}/*.cpp")




