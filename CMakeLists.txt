cmake_minimum_required(VERSION 3.23 FATAL_ERROR)

set(PROJECT_NAME IntroToMultiThreading)
project(${PROJECT_NAME}) 

add_executable(${PROJECT_NAME}
        app/main.cpp

        src/Lesson1.cpp
        src/Lesson2.cpp
        src/Lesson3.cpp
        src/Lesson4.cpp
        src/Lesson5.cpp
        src/Lesson6.cpp
        src/Lesson7.cpp
        src/Lesson8.cpp
        src/Lesson9.cpp
        src/Timer.cpp

        include/Lesson1.h
        include/Lesson2.h
        include/Lesson3.h
        include/Lesson4.h
        include/Lesson5.h
        include/Lesson6.h
        include/Lesson7.h
        include/Lesson8.h
        include/Lesson9.h
        include/Lessons.h
        include/Timer.h
)