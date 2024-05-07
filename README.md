# Table of Contents
1. [Description](#description)
2. [Introduction to Project](#introduction-to-project)
3. [Computer Graphics Concepts Used](#computer-graphics-concepts-used)
4. [User Defined Functions](#user-defined-functions)
5. [Code](#code)
6. [Output/Screen Shots](#output-screen-shots)

## Description
This project is a 3D house architecture visualization implemented using OpenGL. It allows users to explore and interact with a virtual house environment. The project includes various elements such as the outer cover of the house, main door design, rooms, and a kitchen. Users can navigate and view the house from different perspectives using keyboard controls.

## Introduction to Project
This project is a 3D house architecture visualization implemented using OpenGL. It allows users to explore and interact with a virtual house environment. The project includes various elements such as the outer cover of the house, main door design, rooms, and a kitchen. Users can navigate and view the house from different perspectives using keyboard controls.

### Controls through Keys
1. Navigation Controls:
   - Press 'x' to move the viewpoint left.
   - Press 'X' to move the viewpoint right.
   - Press 'y' to move the viewpoint down.
   - Press 'Y' to move the viewpoint up.
   - Press 'z' to move the viewpoint backward.
   - Press 'Z' to move the viewpoint forward.
2. Interaction Controls:
   - Press 'o' to interact with the door, triggering a function called doort(o).
3. Special Key Controls:
   - Use the arrow keys to rotate the viewpoint left, right, up, or down.
   - Use Page Up ('PAGE_UP') to move the viewpoint upward.
   - Use Page Down ('PAGE_DOWN') to move the viewpoint downward.

These controls enable users to explore the 3D house environment dynamically, change viewing angles, and interact with specific elements such as doors, providing an immersive experience of the architectural design.

## Computer Graphics Concepts Used
| Sr. No | Computer Graphics Concept | Description | Usage |
|--------|---------------------------|-------------|-------|
| 1      | Coordinate Systems        | A reference system used to represent object positions. | `glMatrixMode(GL_MODELVIEW)` and `glLoadIdentity()` functions. |
| 2      | Color Rendering            | Specifying colors for objects using RGB components. | `glColor3f(r, g, b)` function. |
| 3      | Primitive Rendering        | Drawing basic geometric shapes in 3D space. | `glBegin(GL_POLYGON)` and `glVertex3f(x, y, z)` functions. |
| 4      | Projection and View Transformation | Setting up perspective projection and viewer's position. | `gluPerspective()` and `gluLookAt()` functions. |
| 5      | Depth Testing and Blending | Ensuring proper object rendering based on depth and controlling transparency. | `glDepthFunc(GL_LEQUAL)`, `glEnable(GL_BLEND)`, `glBlendFunc(GL_SRC_ALPHA, GL_ONE_MINUS_SRC_ALPHA)` functions. |
| 6      | Event Handling | Capturing user input events for interaction and navigation. | `glutKeyboardFunc(keys)` and `glutSpecialFunc(specialKey)` functions. |

## User Defined Functions
| Function Name | Description |
|---------------|-------------|
| `outercover()` | Draws the outer cover or boundary of the 3D scene. |
| `maindoor()` | Renders the main door design. |
| `room1()`, `room2()` | Handles rendering of specific rooms within the house. |
| `kitchen()` | Renders the kitchen within the house. |
| `mid()` | Represents the hall or central area of the architectural visualization. |
| `keys(unsigned char key, int x, int y)` | Handles keyboard input events for interaction. |
| `specialKey(int key, int x, int y)` | Handles special keyboard input events for additional controls. |

## Code
The code for this project includes OpenGL functions and user-defined functions for rendering various elements of the 3D house architecture. Refer to the source code files for implementation details.

## Output/Screen Shots
Screenshots or output images of the 3D house architecture visualization can be included here to showcase the project's visual results.
![Main_Door](https://github.com/rohanthakur336/3D_House_Tour_OpenGL/blob/main/main_door.jpeg)

![Living Room](https://github.com/rohanthakur336/3D_House_Tour_OpenGL/blob/main/living_room.jpeg)

![Kitchen](https://github.com/rohanthakur336/3D_House_Tour_OpenGL/blob/main/kitchen.jpeg)

![Main_Room](https://github.com/rohanthakur336/3D_House_Tour_OpenGL/blob/main/main_room.jpeg)

