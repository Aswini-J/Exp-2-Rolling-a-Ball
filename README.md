# Exp-2-Rolling-a-Ball

<h3>Aim:
  
Algorithm:
</h3>
File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (MiniGame)

Heirarchy -> 3D Object-> Plane [ Right side-> Inspector-> Change the name of plane (Name: Ground) Transform -> Reset Edit -> FrameSelected ]

Scale the ground by giving the scaling value as x=4 y=1 z=4

Heirarchy -> 3D Object-> Sphere [ Right side-> Inspector-> Change the name of plane (Name: Player) Transform -> Reset Edit -> FrameSelected Transform -> Position -> y=0.5]

Hierarchy -> DirectionalLight [ Inspector -> Change the color to white (255,255,255)]

Create a folder in project and name as Materials [Material folder -> Create -> Material (Name: Background) Inspector ->Surface Inputs ->BaseMAp (Choose the color) Metallic map-> 0 Smoothness -> 0.25 Drag the Background to the plane and release the mouse

Material folder -> Create -> Material (Name: Sphere) Inspector ->Surface Inputs ->BaseMAp (Choose the color) Metallic map-> 0 Smoothness -> 0.75 Drag the Sphere material to the ball and release the mouse

Hierarchy -> Player-> Inspector ->Add component-> Rigidbody

Create a new script -> Create a folder in project (Name: Scripts) Hierarchy -> Player -> Inspector-> AddComponent-> NewScripts-> PlayerController( Click create and Add) Copy the PlayerController and drag to Script folder Double click the PlayerController file and type the coding
<h3>Program:</h3>


<h3>Output:</h3>

<h3>Result:</h3>
