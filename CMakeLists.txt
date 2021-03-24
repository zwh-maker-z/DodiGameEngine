project(DodiGameEngine)
add_executable(dodigameenginetest test.cpp)
aux_source_directory(src SRC_LIST)
add_executable(dodigameenginetest ${SRC_LIST})
add_library(dodigameengine ${SRC_LIST})
include_directories(
	${CMAKE_CURRENT_SOURCE_DIR}/include
)
link_directories(
	${CMAKE_CURRENT_SOURCE_DIR}/lib
)
#target_link_libraries()

