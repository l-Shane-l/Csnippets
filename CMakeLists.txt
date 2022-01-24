cmake_minimum_required(VERSION 2.6.0)

# here we specify that the project is C language only, so the default
# C compiler on the system will be used
project(myprogram C)

add_executable(macro macroExp.c)
add_executable(macro2 macroExp.c)