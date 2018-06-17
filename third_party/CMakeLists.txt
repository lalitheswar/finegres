# CMake build : third party


# Configure third party directory
set (THIRD_PARTY_MODULE_PATH "${PROJECT_SOURCE_DIR/third_party}")




# Configure GOOGLE TEST directories
set (GOOGLE_TEST_MODULE_PATH "${THIRD_PARTY_MODULE_PATH/googletest/googletest}")
set (GOOGLE_TEST_INCLUDE_PATH "${GOOGLE_TEST_MODULE_PATH/include}")



# TODO configure GLOG


# set variable for test
set (TEST_THIRD_PARTY_INCLUDE_PATH ${GOOGLE_TEST_INCLUDE_PATH})


# Export vars
set (TEST_THIRD_PARTY_INCLUDE_PATH ${TEST_THIRD_PARTY_INCLUDE_PATH} PARENT_SCOPE)











