file(GLOB PSP_COMMON_SRC "${CMAKE_CURRENT_SOURCE_DIR}/*.cc" "${CMAKE_CURRENT_SOURCE_DIR}/*.c")
add_library(psp-common STATIC ${PSP_COMMON_SRC})
