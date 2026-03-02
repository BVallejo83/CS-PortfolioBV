# CS 330 – 3D OpenGL Scene Project



## Overview

This project demonstrates the development of a fully rendered 3D scene using OpenGL. The scene was constructed using fundamental geometric shapes combined with transformations such as translation, rotation, and scaling. Lighting, shading, and texture mapping were implemented to enhance realism and demonstrate understanding of the graphics rendering pipeline.

The final scene includes modular code organization, functional lighting controls, and properly configured relative file paths to ensure cross-system compatibility.

---

## Features

- Custom 3D object construction using geometric primitives  

- Object transformations (translation, rotation, scaling)  

- Lighting implementation with toggle functionality using the L key  

- Texture mapping using relative paths (no absolute file paths)  

- Modular architecture separating rendering and view logic  

---

## Technical Implementation

The project was structured to separate responsibilities between different components. Rendering logic was managed within the scene management structure, while camera control and view transformations were handled independently. This separation improved readability, debugging efficiency, and maintainability.

Lighting was implemented using shader programs, and textures were loaded using relative paths to ensure the application runs correctly on different systems without dependency on specific directory structures.

Throughout development, emphasis was placed on testing functionality incrementally to ensure transformations, lighting, and texture integration operated correctly together.

---

# Reflection

## How I Approach Designing Software

When designing software, I begin by identifying the core objective and visualizing the final outcome. For this 3D graphics project, I first analyzed the scene requirements and broke the environment into manageable components built from basic shapes. I focused on understanding how transformations would interact in three-dimensional space and how lighting would affect object realism.

This project strengthened my spatial reasoning skills and improved my ability to structure complex systems into modular components. I followed an iterative design process, starting with foundational geometry and gradually layering additional features such as lighting and textures. In future projects, I will continue applying modular design principles and incremental development to improve scalability and maintainability.

---

## How I Approach Developing Programs

During development, I used an iterative implementation strategy. I built and tested one feature at a time to ensure functionality before expanding the project further. When issues arose—such as texture path errors or lighting behavior—I relied on systematic debugging rather than rewriting entire sections of code.

Over time, my development approach evolved from trial-and-error adjustments to structured debugging and validation. I learned the importance of verifying relative file paths, testing shader functionality independently, and confirming feature behavior across different environments.


Iteration played a major role throughout the milestones. Each phase refined object placement, improved lighting realism, and optimized scene structure.

---

## How Computer Science Supports My Educational and Professional Goals

This computational graphics project strengthened my understanding of system-level programming concepts such as memory management, rendering pipelines, modular design, and debugging complex environments. These analytical and problem-solving skills are directly transferable to cybersecurity and secure system development.

From an educational perspective, this project expanded my programming foundation and reinforced structured problem-solving techniques. Professionally, the logical reasoning and debugging discipline developed in this course will support my transition into cybersecurity roles, where identifying vulnerabilities, analyzing system behavior, and troubleshooting technical issues are critical skills.


---


# Repository Contents


- /Source – C++ source files  

- /shaders – Vertex and fragment shader programs  

- /textures – Texture assets used in the scene  

- Design Decisions Document – Project planning and development explanation  


---


# Controls


- L Key – Toggle scene lighting on/off
