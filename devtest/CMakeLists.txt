cmake_minimum_required(VERSION 3.5)

# global vars
set(DEVTESTROOT ${CMAKE_CURRENT_SOURCE_DIR})
message("DEVTESTROOT: " ${CMAKE_CURRENT_SOURCE_DIR})

# inc cm
include(${DEVTESTROOT}/base/base.cm)
include(${DEVTESTROOT}/pipe/pipe.cm)