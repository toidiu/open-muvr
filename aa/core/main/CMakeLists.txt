SET(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}/..)

FILE(GLOB MainSources *.cc)

ADD_LIBRARY(aa-core ${MainSources})
TARGET_LINK_LIBRARIES(aa-core)
