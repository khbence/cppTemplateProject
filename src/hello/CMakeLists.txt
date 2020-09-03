target_sources(
  ${SRC_LIBRARY}
  PRIVATE ${CMAKE_CURRENT_LIST_DIR}/hello.cpp)

target_include_directories(${SRC_LIBRARY} PUBLIC include/hello)