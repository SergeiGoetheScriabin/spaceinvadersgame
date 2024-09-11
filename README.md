# Space Invaders Game

This project involves creating a Space Invaders game from scratch to improve my proficiency in C.

## System Setup

Yay! I got a new PC as of Sep 3, 2024.

To setup this game. I did the following

Using `grep`, I verified that the necessary header files are present:

- **In `/opt/homebrew/Cellar/glew/2.2.0_1/include/GL`**, the `glew.h` file is located.
- **In `/opt/homebrew/Cellar/glfw/3.4/include/GLFW`**, the `glfw3.h` file is located.

## Installation and Compilation

In order to compile, first you need glfw3 and glew. This is to get the OpenGL stuff that is needed.

```sh
# Install GLFW and GLEW using Homebrew
brew install glfw3 glew

# Compile the C++ program
g++ main.cpp -std=c++11 -o main \
    -I/opt/homebrew/Cellar/glew/2.2.0_1/include \
    -I/opt/homebrew/Cellar/glfw/3.4/include \
    -L/opt/homebrew/Cellar/glew/2.2.0_1/lib \
    -L/opt/homebrew/Cellar/glfw/3.4/lib \
    -lglfw -lGLEW -framework OpenGL
