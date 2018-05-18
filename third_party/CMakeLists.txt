# CMake build : third party


#configure third party directories
set (THIRD_PARTY_MODULE_PATH "${PROJECT_SOURCE_DIR/third_party}")

#configure GOOGLE TEST directories
set (GOOGLE_TEST_MODULE_PATH "${THIRD_PARTY_MODULE_PATH/googletest/googletest}")
set (GOOGLE_TEST_INCLUDE_PATH "${GOOGLE_TEST_MODULE_PATH/include}")

#TODO configure GLOG

#export vars
set (TEST_INCLUDE_PATH ${GOOGLE_TEST_INCLUDE_PATH} PARENT_SCOPE)











