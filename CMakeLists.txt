cmake_minimum_required(VERSION 3.29)
project(klotik_learn_c C)

set(CMAKE_C_STANDARD 23)

add_executable(klotik_learn_c main.c
        solutions/D04/task_01.c
        solutions/D04/task_02.c)
