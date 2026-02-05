# Luminous-Engine-Game-Engine-Editor-
*3 months*, *2025*, *C++*, *Engine*, *Group*, *Vulkan*, *Editor*

### Project Name : **Luminous Engine**
*Quick description* : Isart Digital Project, Game Engine & Editor made in C++ with the Vulkan API.
*Author* : Aodrenn, Ethan, Landry, Maxence

![luminous](https://github.com/user-attachments/assets/f36507d9-6c58-493a-81a2-21395375ed8d)<br>



**Engine / Editor**  
Luminous is a custom game engine and editor developed by a team of four.    
The project focuses on real-time rendering, engine architecture,    
and editor tooling built from the ground up.    

<img width="512" height="281" alt="image" src="https://github.com/user-attachments/assets/4e9df731-b38f-45d6-86f4-5fdc5ffbe6af" /><br>




**Libraries**  
Luminous is built using the following libraries :  
Vulkan – Low-level rendering backend  
ImGui – Editor user interface  
GLFW – Window and input handling  
Assimp – 3D model importing  
Jolt Physics – Physics simulation  

<img width="500" height="175" alt="image" src="https://github.com/user-attachments/assets/044ccec0-c19b-4286-9953-a675d9b7a5dc" /><br>



**Logger**  
The engine includes a centralized logging system used across  
all engine modules.  
It allows clear debugging, error reporting,  
and information tracking during development.  

<img width="500" height="125" alt="image" src="https://github.com/user-attachments/assets/36976876-8fc1-40fe-bda7-5a3dd8dc156c" /><br>



**Resource Manager**  
The resource manager is class that can create,modify,delete any  
of the resources that we need in the engine, all inherit from the resource class,  
like Meshes,Models,Textures,Shaders...  

<img width="500" height="125" alt="image" src="https://github.com/user-attachments/assets/f3a22c68-fad7-4d73-93d2-f3c3a447df93" /><br>




**Model Loading**  
Luminous supports 3D model importing using Assimp.  
Models are processed and converted into a Mesh Class that   
we can create instances of using the resource manager.  

<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/14074c9d-b172-4b41-8500-8e93b4b17187" /><br>




**Entity Component System**  
The engine is built around an Entity Component System architecture.  
Entities are composed of modular components, allowing flexible  
scene editing.  

<img width="450" height="250" alt="image" src="https://github.com/user-attachments/assets/a293649a-8291-47c7-9fbc-a55dce7cb2fb" /><br>




**Rendering & Lighting**  
Luminous supports real-time lighting,  
Lights are coded directly through shader code with GLSL.  

<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/7736438b-1998-46c3-b15d-d137c1bd349c" /><br>
<img width="450" height="250" alt="image" src="https://github.com/user-attachments/assets/0af4f8db-10a0-4e49-950d-00b7df421d56" /><br>  




**Directional Lights** – Used for global lighting  

<img width="394" height="222" alt="image" src="https://github.com/user-attachments/assets/f41b5c90-b2eb-4e13-8f84-318f2be41b22" /><br>

**Point Lights** – Local light sources affecting nearby objects  

<img width="399" height="265" alt="image" src="https://github.com/user-attachments/assets/64780cd6-5b2b-4414-aeb6-13d30427c63a" /><br>





**Physics**  
The engine integrates a physics system completely wrapped around Jolt,  
It supports collider-based physics for entities,  
allowing interaction and basic simulation inside the engine.  

![physics](https://github.com/user-attachments/assets/f0cd3713-a470-421a-92ca-bc272249c28a)


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

![unnamed](https://github.com/user-attachments/assets/66ce69a2-c0cc-46b5-a0dd-01437ec298df)





