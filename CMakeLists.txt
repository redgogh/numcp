cmake_minimum_required(VERSION 3.26)
project(sci)

set(CMAKE_CXX_STANDARD 23)

file(GLOB SOURCES
  "*.cpp"
)

add_executable(${PROJECT_NAME} ${SOURCES})
