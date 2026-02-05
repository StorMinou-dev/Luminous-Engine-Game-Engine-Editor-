# Luminous-Engine-Game-Engine-Editor-
*3 months*, *2025*, *C++*, *Engine*, *Group*, *Vulkan*, *Editor*

### Project Name : **Luminous Engine**
*Quick description* : Isart Digital Project, Game Engine & Editor made in C++ with the Vulkan API.
*Author* : Aodrenn, Ethan, Landry, Maxence

[Title Image]  

**Engine / Editor**  
Luminous is a custom game engine and editor developed by a team of four.    
The project focuses on real-time rendering, engine architecture,    
and editor tooling built from the ground up.    

[Editor Overview Image]  


**Libraries**  
Luminous is built using the following libraries :  
Vulkan – Low-level rendering backend  
ImGui – Editor user interface  
GLFW – Window and input handling  
Assimp – 3D model importing  
Jolt Physics – Physics simulation  
[Libraries Image]  


**Logger**  
The engine includes a centralized logging system used across  
all engine modules.  
It allows clear debugging, error reporting,  
and information tracking during development.  
[Logger Image]  


**Resource Manager**  
The resource manager is class that can create,modify,delete any  
of the resources that we need in the engine, all inherit from the resource class,  
like Meshes,Models,Textures,Shaders...  
[Resource Manager Image]  


**Model Loading**  
Luminous supports 3D model importing using Assimp.  
Models are processed and converted into a Mesh Class that   
we can create instances of using the resource manager.  
[Model Loading Image]  


**Entity Component System**  
The engine is built around an Entity Component System architecture.  
Entities are composed of modular components, allowing flexible  
scene editing.  
[ECS Image]  


**Rendering & Lighting**  
Luminous supports real-time lighting,  
Lights are coded directly through shader code with GLSL.  
[Shader Code]  


**Directional Lights** – Used for global lighting  
**Point Lights** – Local light sources affecting nearby objects  
[Lighting Image]  


**Physics**  
The engine integrates a physics system completely wrapped around Jolt,  
It supports collider-based physics for entities,  
allowing interaction and basic simulation inside the engine.  
[Physics Image]  

**My Role**  
On this project, as well as helping my team mates when they are  
in difficulties, i got to implement these features :  
Resource Manager – Asset loading, caching, and lifetime management  
Window Manager – Window creation and management using GLFW  
Input Manager – Keyboard and mouse input handling  
Scene System – GameObjects showing on the scene    
Lighting – Implementation of directional and point lights  
Viewport to ImGui – Rendering the engine viewport inside the editor UI  
Colliders – Integration of collider components into the physics system  




