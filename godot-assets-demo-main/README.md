# Godot Procedural Asset Spawner (AI Training Sandbox)

## Overview

This project is a technical demonstration of using the **Godot Engine 4** to build automated, procedural environments for AI data collection and digital asset management. It showcases how to programmatically spawn, manage, and randomize digital assets (3D meshes with physics) within a controlled environment—a common requirement for generating synthetic data for Computer Vision or Reinforcement Learning models.

## Key Features

* **Procedural Generation:** Automated spawning of 3D assets using GDScript, avoiding manual placement and enabling infinite dataset generation.
* **Dynamic Properties:** Assets are spawned with randomized spatial offsets and dynamically generated materials (albedo colors) to simulate dataset variance.
* **Physics Simulation:** Full integration of Godot's `RigidBody3D` and `CollisionShape3D` to ensure realistic object interaction, gravity, and resting states.
* **Lifecycle Management:** Engine-level optimization using code-based `Timer` nodes to manage the spawn rate and automatically halt the process once the target asset quota is reached.
* **Modular Architecture:** The spawner script relies on `@export` variables for `PackedScenes`, allowing non-programmers or other team members to swap the target digital asset directly from the Godot Inspector without touching the codebase.

## Technical Stack

* **Engine:** Godot Engine 4.x
* **Language:** GDScript (Object-Oriented approaches)
* **Concepts:** Memory Management (Instancing), 3D Vectors, Material Overrides, Physics Server.

## How to Run

1. Clone this repository.
2. Import the project folder into Godot 4.
3. Open `main.tscn`.
4. Press `F5` (Play) to start the simulation.

## Demonstration

https://github.com/user-attachments/assets/9ad827a2-2fce-4e20-8342-fdefa954ef0f

\---



