cmake_minimum_required (VERSION 3.1.0 FATAL_ERROR)
project (CxqWeb-Source)
add_executable(makequiz.cgi cxqweb-source-main.cc)
add_executable(submitquiz.cgi cxqweb-source-gradeit.cc)
set_property(TARGET makequiz.cgi PROPERTY CXX_STANDARD 11)
set_property(TARGET makequiz.cgi PROPERTY CXX_STANDARD_REQUIRED ON)
set_property(TARGET submitquiz.cgi PROPERTY CXX_STANDARD 11)
set_property(TARGET submitquiz.cgi PROPERTY CXX_STANDARD_REQUIRED ON)
