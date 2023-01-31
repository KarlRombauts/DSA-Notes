# Installing a C++ Compiler (Linux)

Depending on your linux disto, you may or may not already have a C++  compiler installed. You can easily check this by running the following command in the terminal:

```
g++ --version
```

If g++ is not installed, we need to install `build-essential` and `gbd`.

`build-essential` is a package on Linux distributions which contains the essential build tools for compiling software from source code. It includes the GNU Compiler Collection (GCC) and other libraries and tools such as make.

`gbd` is a powerful debugger used to debug programs written in C, C++, and other languages. It helps developers find bugs in their programs by allowing them to step through code line by line, set breakpoints, and view variables and their values.

## Installation Instuctions


### Ubuntu/Debian

1. Open a terminal window and run the following commands 
    ```
    sudo apt-get update
    sudo apt-get install build-essential gdb
    ```

2. Enter your password if prompted

3. Follow the on-screen instructions to install the packages

### Arch

I assume you know what you are doing if you are running arch, but here are the steps just in case.

1. Open a terminal window and run the following command: 
   ```
   sudo pacman -S base-devel gdb
   ```

2. Enter your password if prompted

3. Follow the on-screen instructions to install the packages
