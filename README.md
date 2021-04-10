# WebGPU Graphics Programming: Step-by-Step 

WebGPU is the next-generation graphics API and future web standard for graphics and compute, aiming to provide modern 3D graphics and 
computation capabilities with the GPU acceleration. To help you be familiar with this new graphics API and able to build your WebGPU 
applications, I will create a YouTube video series about WebGPU programming. Each video episode will discuss a complete easy-to-follow 
WebGPU application, and this repository contains all the code examples used in the YouTube video series.

The YouTube video series uses the real-world sample apps to explain the WebGPU basics, shader program, GPU buffer, and rendering pipeline. 
From this video series, you will learn how to create primitives and simple objects in WebGPU. As you gradually progress through the video series, 
you will get to grips with advanced WebGPU topics, including 3D transformation, lighting calculation, colormaps, and textures. At the same time, 
you will learn how to create advanced 3D WebGPU objects, including various 3D wireframes, 3D shapes, simple and parametric 3D surfaces with 
colormaps and textures, as well as 3D surface plots and fractal graphics described by complex functions. In addition, you will explore new 
WebGPU features, such as compute shader and storage buffer, and how to use them to simulate large particle systems.

By the end of this video series, you will have the skill you need to build your own GPU-accelerated graphics and computing on the web with the WebGPU API.   

## Sample Objects 
Here are some sample objects created using the WebGPU API, which I will discussed in my video series.

### Klein Bottle created using WebGPU:
![klein-bottle](assets/klein-bottle.png)

### Wellenkugel Surface created using WebGPU:  
![wellenkugel](assets/wellenkugel.png) 

### 3D Sinc Surface created using WebGPU:
![sinc](assets/sinc.png) 

### Multiple-Textures created using WebGPU:
![textures](assets/textures.png) 

### Multiple Objects on a Scene created using WebGPU:
![nultiple-objects](assets/multiple-objects.png) 

### 3D Surface Plots for Complex Functions created using WebGPU:
![complex-surface](assets/complex-surface.png) 

### Another Surface Plot for Complex Function:
![complex-surface1](assets/complex-surface1.png) 

## Building

This repository arganizes all samples with the git submodules. You can click on the link for the sample app you are interested and clone or download it 
to your local machine. The sample apps are built with TypeScript and bundled using WebPack. Building the apps requires an installation of Node.js.

The following steps shows how to run the sample apps:

* Install dependencies with the command: **npm install**.
* Compile and bundle the app with the command: **npm run watch**.
* Run live-server from VS-Code and then navigate to **http://localhost:5500** to view the app.
 
