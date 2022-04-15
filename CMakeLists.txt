project(ExampleProject)

add_subdirectory(Test)
add_executable(example main.c test.c test2.c)