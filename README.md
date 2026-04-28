# VR Interior Design App

## Overview

The VR Interior Design App is an immersive virtual reality application developed using Unity for designing and customizing interior spaces in real time. The project allows users to visualize room layouts, place furniture, modify materials, and interact with objects inside a fully immersive VR environment.

The main goal of this project is to improve interior design planning by helping users experience room customization before actual implementation.

## Features

* Full VR environment integration
* Furniture spawning and placement
* Object selection and interaction
* Material customization (walls, floors, furniture)
* Advanced furniture placement system
* Save and load system
* Cloud-based save system concept
* Improved user interface with simple navigation
* Expanded furniture library
* Collision detection and object alignment
* Performance optimization and debugging

## Technologies Used

* Unity Engine
* C# Programming
* Meta Quest 3
* Unity Asset Store
* Poly Haven
* Blender (for 3D assets and models)

## Modules

### 1. User Interface Design

A clean and simple interface was created for easy navigation. Buttons were added for:

* Furniture selection
* Material customization
* Save and load functions
* Room navigation
* Reset functionality

### 2. Furniture Spawning and Placement

Users can select furniture such as sofas, chairs, tables, and beds and place them inside the virtual room. Proper alignment and collision detection were implemented to prevent floating and overlapping.

### 3. Object Selection and Interaction

Users can select, move, rotate, and arrange furniture objects easily using interactive controls.

### 4. Material Customization

Users can change wall colors, floor textures, and furniture materials such as wood, marble, paint, and tiles for better visualization.

### 5. Save and Load System

The application stores furniture positions, material selections, and room layouts so users can continue their designs later.

## Challenges Faced

* Furniture floating above the floor
* Incorrect object selection
* Save and load inconsistencies
* Lag while loading 3D models
* UI responsiveness issues
* Object alignment problems

## Solutions Implemented

* Collider correction and ground detection
* Improved object positioning logic
* Optimized 3D models for better performance
* Updated save logic for accurate restoration
* UI improvements for smoother interaction
* Repeated testing and debugging for stability

## Sample Code Snippet

```csharp
using UnityEngine;

public class FurnitureSpawner : MonoBehaviour
{
    public GameObject furniturePrefab;
    public Transform spawnPoint;

    public void SpawnFurniture()
    {
        Instantiate(furniturePrefab, spawnPoint.position, Quaternion.identity);
    }
}
```

## Future Enhancements

* AI-based furniture recommendations
* Multi-room customization
* Cloud synchronization across devices
* Real-time collaboration for multiple users
* Advanced lighting simulation
* Smart home integration

## References

* Unity Official Documentation
* Unity Asset Store
* Poly Haven
* Blender Documentation
* Mastering UI Development with Unity
* The VR Book: Human-Centered Design for Virtual Reality

## Conclusion

This project successfully demonstrates how virtual reality can improve interior design planning by providing users with an immersive and interactive experience. It combines practical VR development, UI design, and 3D visualization to create a useful real-world application for interior customization.

---




