# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/muhammadxy/The-Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)
##Demo[https://drive.google.com/file/d/1uYyppBXmPk5GHwLAuN18jzIIB9ZcbnHf/view?usp=drive_link ]
![The Maze Gif](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/bc961dcd5fb040c7ba1c3d7f5c640acdc2b04a34.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230316%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230316T090129Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cf63f5d6bbe34e2ace060f3127a7c92052c1cdcf894d7976ba3945dc2928bc90)

