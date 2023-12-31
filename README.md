# Graphics_course_renderer
Basic renderer implementing both Pathtracing and Photonmapping algorithms developed for the Informática Gráfica 2022/2023 course at Universidad de Zaragoza, developed alongside ![@llauragonzalezz](https://github.com/llauragonzalezz)
![twin_peaks](https://github.com/Sondeluz/Graphics_course_renderer/assets/56542714/4b0721ea-b23f-4703-9c83-e8b9faf11b27)

![35_point_lights_final_render](https://github.com/Sondeluz/Graphics_course_renderer/assets/56542714/143493cc-6e11-402c-ae28-ad1479fc1d3a)

## Features
- Highly multithreaded
- Uses acceleration structures (BVH trees)
- Basic support for .obj files and textures
- Implements Constructive Solid Geometry
## Requirements
- C++17
- CMake
## Building and running
- Tweak the main.cpp file to select your scene, the algorithm to use and the image qualty (resolution and rays per pixel)
- Run 'cmake build . && make'
## Note
Some documentation (algorithm explanations, etc.) have been removed from the code. Also, some comments in Spanish may have slipped in.
