If you get output similar to the following:
```
```
Try this: `sudo ln -s /usr/lib/x86_64-linux-gnu /usr/lib64`

<details>
<summary>If you get an error like this :</summary>
```
-- The C compiler identification is GNU 6.3.0
-- The CXX compiler identification is GNU 6.3.0
-- Check for working C compiler: /home/jconnell/github/PROJ/tools/bin/gcc
-- Check for working C compiler: /home/jconnell/github/PROJ/tools/bin/gcc -- broken
CMake Error at /usr/local/share/cmake-3.11/Modules/CMakeTestCCompiler.cmake:52 (message):
  The C compiler

    \"/home/jconnell/github/PROJ/tools/bin/gcc\"

  is not able to compile a simple test program.

  It fails with the following output:

    Change Dir: /home/jconnell/github/PROJ/buildLinux/CMakeFiles/CMakeTmp

    Run Build Command:"/usr/bin/make" "cmTC_11310/fast"
    /usr/bin/make -f CMakeFiles/cmTC_11310.dir/build.make CMakeFiles/cmTC_11310.dir/build
    make[1]: Entering directory '/mnt/c/github/PROJ/buildLinux/CMakeFiles/CMakeTmp'
    Building C object CMakeFiles/cmTC_11310.dir/testCCompiler.c.o
    /home/jconnell/github/PROJ/tools/bin/gcc    -o CMakeFiles/cmTC_11310.dir/testCCompiler.c.o   -c /home/jconnell/github/PROJ/buildLinux/CMakeFiles/CMakeTmp/testCCompiler.c
    Linking C executable cmTC_11310
    /usr/local/bin/cmake -E cmake_link_script CMakeFiles/cmTC_11310.dir/link.txt --verbose=1
    /home/jconnell/github/PROJ/tools/bin/gcc      -rdynamic CMakeFiles/cmTC_11310.dir/testCCompiler.c.o  -o cmTC_11310
    /usr/bin/ld: cannot find crt1.o: No such file or directory
    /usr/bin/ld: cannot find crti.o: No such file or directory
    collect2: error: ld returned 1 exit status
    CMakeFiles/cmTC_11310.dir/build.make:86: recipe for target 'cmTC_11310' failed
    make[1]: *** [cmTC_11310] Error 1
    make[1]: Leaving directory '/mnt/c/github/PROJ/buildLinux/CMakeFiles/CMakeTmp'
    Makefile:126: recipe for target 'cmTC_11310/fast' failed
    make: *** [cmTC_11310/fast] Error 2
```
</details>
Then do something like `bcde`


## See also:
[nothing](nothing)
