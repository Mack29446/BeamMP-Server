include_directories("${PROJECT_SOURCE_DIR}/deps/asio/asio/include")
include_directories("${PROJECT_SOURCE_DIR}/deps/rapidjson/include")
include_directories("${PROJECT_SOURCE_DIR}/deps/websocketpp")
include_directories("${PROJECT_SOURCE_DIR}/deps/commandline")
include_directories("${PROJECT_SOURCE_DIR}/deps/sol2/include")
include_directories("${PROJECT_SOURCE_DIR}/deps")

add_subdirectory("${PROJECT_SOURCE_DIR}/deps/commandline")
add_subdirectory("${PROJECT_SOURCE_DIR}/deps/sol2")
