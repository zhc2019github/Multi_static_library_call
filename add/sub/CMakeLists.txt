message("sub lib")
aux_source_directory(. SRC_LIST)
add_library(mathsub STATIC ${SRC_LIST})