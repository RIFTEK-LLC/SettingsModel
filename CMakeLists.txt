cmake_minimum_required(VERSION 3.13)



###############################################################################
## PROJECT
## name and version
###############################################################################
project(SettingsModel LANGUAGES CXX)



###############################################################################
## INCLUDING SUBDIRECTORIES
## Adding subdirectories according to the configuration
###############################################################################
# src
add_subdirectory(src)
if (${PARENT}_UTILS_EXAMPLES)
    add_subdirectory(example)
endif()
