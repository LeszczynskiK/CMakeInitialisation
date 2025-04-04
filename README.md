# CMakeInitialisation
How to initialise CMake in project
This is also base for GoogleTest(with CMake usage)  

1. Make main folder for your project

2. Add files with .hpp and .cpp extention which fill your project tasks

3. Add CMake initialisation file .txt names CMakeLists.txt

4. Complete CMakeLists.txt like in CMakeLists.txt in this project

5. Generate cmake compilation files: cmake . . (. this directory, . this overhead directory)

6. If generated, build your project: cmake --build . (. this directory - build here!)

7. If build, you can run your program by ./name_of_program 
Name of program is written in add_executable(name_of_program, ....)

8. When threads are added, include on the end of CMakeLists.txt this:  
target_link_libraries(MyExecutable pthread)  
