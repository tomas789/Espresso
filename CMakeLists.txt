cmake_minimum_required(VERSION 3.13)

project(espresso)



file(GLOB espresso_src
     "src/*.c"
)


add_executable(espresso ${espresso_src})
set_property(TARGET espresso PROPERTY CXX_STANDARD 20)
