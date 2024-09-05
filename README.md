# Space Invaders Game

Making a Space Invaders game from scratch to help myself learn C better.

Yay! I got a new computer, as of Sep 5 2024.

Using `grep`, I was able to find the following:

- **In `/opt/homebrew/Cellar/glew/2.2.0_1/include/GL`**, I have `glew.h`.
- **In `/opt/homebrew/Cellar/glfw/3.4/include/GLFW`**, I have `glfw3.h`.

To compile my code, I use the following command:

```sh
g++ main.cpp -std=c++11 -o main \
    -I/opt/homebrew/Cellar/glew/2.2.0_1/include \
    -I/opt/homebrew/Cellar/glfw/3.4/include \
    -L/opt/homebrew/Cellar/glew/2.2.0_1/lib \
    -L/opt/homebrew/Cellar/glfw/3.4/lib \
    -lglfw -lGLEW -framework OpenGL
