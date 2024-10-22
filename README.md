# CPU Renderer
A very simple rasterized renderer written for two primary purposes:
1. To familiarize myself with the Zig programming language, which is a joy to use.
2. To learn the basics of rendering meshes via rasterization.

Though the project is quite simple, I had a lot of fun making it and would love to reimplement a more fully featured version in the future. It's a great project for learning a new language.

> [![YouTube](http://i.ytimg.com/vi/DuxeTrA3zwo/hqdefault.jpg)](https://www.youtube.com/watch?v=DuxeTrA3zwo)
>
> Demo on YouTube, showing off the basic functionality.

## Features
The featureset is very small, as I was only interested in implementing the related math and getting something on screen.
- All related math implemented manually.
- Orthographic and perspective projection, as well as wireframe/solid triangle rendering using barycentric coordinates for the colors.
- Camera system with first person mouse look and the ability to fly around freely.

A number of basic features have not been implemented, such as:
- Depth buffering.
- Proper triangle rasterization to avoid seams.
- Texture mapping.
- etc.
