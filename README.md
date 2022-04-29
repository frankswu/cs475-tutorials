# CS475 / CS675 OpenGL tutorials

资源URL：
https://methi1999.github.io/2020/08/19/opengl.html#:~:text=OpenGL%20was%20deprecated%20in%20macOS,versions%20such%20as%20macOS%2010.15.


These are OpenGL programming tutorials for the CS475/CS675 : Computer Graphics course.

The OpenGL version used is 3.3+

Please look at the README files of the corresponding tutorials for more information.



make 输出的编译脚本 修改 -lGL 变成 -framework OpenGL

## 实际调用命令
➜  /Users/frankswu/Documents/work/opengl_demo_workspace/cs475-tutorials/Tutorial_00 git:(test_demo) ✗ >make
g++ -I/usr/local/include 00_glInit.cpp -o 00_glInit -L/usr/local/lib  -lGL -lGLEW -lglfw
➜  /Users/frankswu/Documents/work/opengl_demo_workspace/cs475-tutorials/Tutorial_00 git:(test_demo) ✗ >g++ -I/usr/local/include 00_glInit.cpp -o 00_glInit -L/usr/local/lib   -lGLEW -lglfw -framework OpenGL

