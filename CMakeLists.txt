project(HttpParser VERSION 1.0 LANGUAGES C)

add_library(HttpParser http_parser.h http_parser.c)

target_include_directories(HttpParser PUBLIC .)
