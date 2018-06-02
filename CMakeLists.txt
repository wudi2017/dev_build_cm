cmake_minimum_required(VERSION 3.5)

# global vars
set(CMSRCROOT ${CMAKE_CURRENT_SOURCE_DIR})
message("CMSRCROOT: " ${CMSRCROOT})
set(CMRUNROOT ${PROJECT_BINARY_DIR})
message("CMRUNROOT: " ${CMRUNROOT})
set(CMOUT ${CMRUNROOT}/out)
message("CMOUT: " ${CMOUT})
file(MAKE_DIRECTORY ${CMOUT})

# add sub cm
add_subdirectory(${CMSRCROOT}/devtest)