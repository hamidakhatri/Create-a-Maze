# Create-a-Maze

## Overview
This project involved creating an interactive VR maze using the XR toolkit and Snaps prototype package. The goal was to design a maze that includes interactable elements, such as a key to open a door, to enhance the immersive experience. This assignment helped me familiarize myself with the XR Rig, locomotion system, and XR Direct/Ray Interactors, laying the foundation for creating an explorable and interactive VR environment.

## Requirements Checklist
- The maze includes at least four turns.
- The maze includes at least two dead ends.
- The environment objects are aligned to the grid.
- The player uses a grabbable object (key) to progress further.
- A win state is activated upon entering the final section (the red zone).
- The maze must be playable with the VR headset.
- The project is on GitHub and marked public.

## Challenges and Solutions
- **Grabbing the Key Object:** One of the main challenges was making the key object interactable and grabbable. Initially, the key was difficult to pick up due to improper collider settings. After adjusting the collider and experimenting with different settings in the XR toolkit, I was able to successfully make the key interactable.
- **Locomotion System:** Integrating the locomotion system to ensure smooth movement through the maze was another hurdle. By thoroughly reviewing the XR toolkit documentation and leveraging community forums, I managed to implement a functional locomotion system.
- **Aligning Objects to Grid:** Ensuring that all objects were properly aligned to the grid required careful placement and adjustments. This was crucial for maintaining the structural integrity of the maze.
- **Win State Activation:** Setting up the win state required creating a trigger area in the final section of the maze. This was achieved by using a collider and scripting the event to activate upon the player's entry.

## Additional Assets and Tools
- **Integrated Tools:** Used the XR toolkit and Snaps prototype package for building the maze and interactable objects.
- **Additional Models:** Added some custom models to enhance the visual appeal of the maze.
- **Helpful Resources:** The Unity XR toolkit documentation and community forums were invaluable in overcoming various challenges and learning how to effectively use the tools.

This assignment was a great learning experience, providing hands-on practice with VR development and version control using GitHub. The challenges faced during the project helped in gaining a deeper understanding of the XR toolkit and its components. The resources and community support were crucial in overcoming obstacles and achieving a functional and interactive VR maze.
