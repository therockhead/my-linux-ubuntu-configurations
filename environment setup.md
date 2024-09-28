UBUNTU LINUX 22.04 LTS JAMMY JELLY FISH

GCC/G++ compilers:
-------------------------
**install command:** 

```sudo apt install build-essential```

**check gcc**: 

```gcc --version```

**check g++**: 

```g++ --version```

**compile a C file**: 

``` gcc test.c -o test ```

(-o is used to create a binary test file from the C file named "test.c)

then, **to run the binary file**: ./test (which runs the code in the terminal)

**In case of C++:** all the things same as C but with g++ instead of gcc


c++ 14 build file for sublime (Linux):
--------------------------------------
tools->build system->create new one->paste->save as "c++14.sublime.build"
```
{
"cmd" : ["g++ -std=c++14 $file_name -o $file_base_name && timeout 4s ./$file_base_name<inputf.in>outputf.in"], 
"selector" : "source.c",
"shell": true,
"working_dir" : "$file_path"
}
```
To run C/C++ file in Sublime Text Editor:
-----------------------------------------
1. ```Alt+3``` to open three windows side by side
2. create ```inputf.in``` and ```outputf.in``` files
3. paste the input in ```inputf.in``` file and go back to the code file and press ```Ctrl+Shift+B``` to build the file


JDK setup:
----------
```sudo apt install openjdk-18-jdk```
