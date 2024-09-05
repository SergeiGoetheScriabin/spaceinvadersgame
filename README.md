# spaceinvadersgame
making space invaders game from scratch to help myself learn C better.

yay! i got a new computer

Using grep I was able to find this.

in my opt/homebrew/Cellar/glew/2.2.0_1/include/GL

I have glew.h.

In /opt/homebrew/Cellar/glfw/3.4/include/GLFW

I have glfw3.h

g++ main.cpp -o main
-I/opt/homebrew/Cellar/glew/2.2.0_1/include
-I/opt/homebrew/Cellar/glfw/3.4/include
-L/opt/homebrew/Cellar/glew/2.2.0_1/lib
-L/opt/homebrew/Cellar/glfw/3.4/lib
-lglfw -lGLEW -framework OpenGL

Doing this let me compile it.
