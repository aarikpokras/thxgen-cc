cake_minimum_required(VERSION 3.13)

project (thxgen)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES thxgen.cc)

add_executable(thxgen ${SOURCE_FILES})
