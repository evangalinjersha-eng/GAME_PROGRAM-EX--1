# GAME_PROGRAM-EX--1
EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine
Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

Procedure
Create a New Material:

Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.
Apply Base Color:

Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.
Add Emissive Effect:

Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.
Control Roughness:

Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.
Control Metallic Property:

Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.
Save and Apply Material:

Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

##OUTPUT
<img width="1536" height="1024" alt="513751527-c4756af5-a1c2-40a8-a90e-7937f2936df4" src="https://github.com/user-attachments/assets/1ab729da-4687-4c4f-892a-81de956d54d4" />
<img width="1192" height="791" alt="441625267-3aaea163-8335-42c9-af3c-46adac71cb00" src="https://github.com/user-attachments/assets/d878e666-4005-4aba-9b6e-7fdc61ba62f5" />

##Result
Successfully implemented a material in Unreal Engine showcasing:

Emissive glow using emissive color and intensity.
Variable surface roughness to simulate different textures.
Metallic appearance adjustment to reflect light like real-world metals.
This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.

