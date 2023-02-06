## 选择一个图形库

### 收集：

在 Rust 的图形上的包有很多，

有从 Rust 发展出来的 WebGPU 方向，有Sven Nilsen的 Piston-Graphics.

### 2D；

I found a post it is a good experience post for graphics in rust 
https://medium.com/@mfriedrich/get-started-with-graphics-programming-in-rust-d98c26e41e5f.
the post said he simple base to draw text on rectangle.

The "Piston" I did not understand the name in English what metaphor mean https://www.piston.rs/ . They have a lot librarys.

keyword for me : SDL2, 

### SDL2

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via `OpenGL` and `Direct3D` .
是多媒体库，有各种硬件上接口，比如键盘、音频、视频。
是跨平台的，不同平台会选择到对应的接口，比如视频接口中，windows会选择的DX，macos会选择到metal这样的逻辑。

### OpenGL Rust

https://rust-tutorials.github.io/learn-opengl/basics/index.html#prior-knowledge
在Rust中启用OpenGL的调用，

### Rust 有着很多游戏引擎

比如 Ggez, Bevy, Piston, Amethyst(这个已经停止了)

### 没有纯Rust的图形
不过大部分都可以使用rust来调用
I like https://kylemayes.github.io/vulkanalia/


### 数学实践
https://raytracing.github.io/books/RayTracingInOneWeekend.html#overview