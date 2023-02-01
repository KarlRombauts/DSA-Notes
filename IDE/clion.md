# <img src="../images/1d9db5503638514afce8b5c094aee438652d5ec01ba1f1bb6110037a62f57650.png" width=50 style="margin-bottom: -10px">  Getting Started with CLion

CLion is an Integrated Development Environment (IDE) for C++ development. It is developed by JetBrains and provides a powerful set of features for C++ development, such as syntax highlighting, code refactoring, code completion, version control, debugging, and more. CLion is designed to help developers quickly and efficiently develop their C++ projects, and provides a modern, well-rounded development environment. It is also compatible with a wide range of C++ compilers, including GCC and Clang.

Jetbrains software is normally not free to use, but they do provide a free licence to all their IDEs for students, teachers, open-source contributors, and non-commercial contributors. This licence allows you to use JetBrains software for educational, open-source and non-commercial purposes. The licence is valid for one year, after which you can renew the licence if they are still eligible.

### Step 1: Install CLion

Download and install CLion from https://www.jetbrains.com/clion/download.

![picture 3](../images/2665889961eaab1267beffbb38f9fdf211eb1a0e7a17298429495322eee74884.png)  

You can also download the Toolbox App [here](https://www.jetbrains.com/toolbox-app/), which allows you to easily download and update JetBrains products.

### Step 2: Create a new project

1. Launch CLion and select "New Project" from the Welcome screen.

    ![picture 4](../images/a146250bfa12a52b29848a96c2559fbab9303e63f05c5114bb140b6953eef1f6.png)  

2. Select C++ Executable from the list of project templates.

    ![picture 5](../images/ed41b8a372f38297c55e3706cb0b53e4c50923c6ca0e425f1fac0e08b446c628.png)  

3. Choose a location and name the project "cpp-helloworld"
   
4. Set the language standard to C++20

5. Click on **Create**

6. Set the project name to "cpp-helloworld" and accepts the default settings in the Project Wizard

    ![picture 6](../images/ff5c425442bf72adf0bfc9b61fc39fb80d44c2afb75fd531e85a9e25c658957b.png)  

    You should now be greated with a main.cpp file that contains
    ```cpp
    #include <iostream>

    int main() {
        std::cout << "Hello, World!" << std::endl;
        return 0;
    }
    ```
### Step 3: Building Project

To compile and run your program, click the ▶️ button in the toolbar (`Ctrl + R`).

![picture 7](../images/84608ce58a955a7e90b78042282662816cd48ed8356f412527edab457a842523.png)  
