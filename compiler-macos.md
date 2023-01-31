# Installing a C++ Compiler (MacOS)

To get started with C++ on MacOS, we need to first install Xcode Command Line Tools. These are a collection of command line based tools for developing software on Mac OS X. They are necessary for C++ development because they provide the compilers and other tools needed to build and run C++ programs on the Mac. 

Amongst other things, this will install
- g++ (compiler for C/C++ files)
- gcc (compiler for C files)
- clang (compiler for C/C++ files)
- make (build tool)

## Installation Instuctions

1. Open the Terminal application

2. Type the following command: 
   ```
   xcode-select --install
   ```

3. Click the "Install" button when prompted to confirm the installation.

![picture 2](images/fe87008a7c866c20b2ddb5e3c1a8f10b469af425e8de46c0b45f7c6d1055bf49.png)  

4. Agree to the license agreement

5. Wait for the installation to finish

6. You can verify the installation by typing the following command: 
   ```
   xcode-select --version
   ```
   This should return the version of Xcode Command Line Tools installed on your Mac