# Unit 2 - Week 3 - Objects

## Slides
https://myuva-my.sharepoint.com/:p:/g/personal/jcb2h_virginia_edu/ESjYUJDLpExOqvlfpCVEijYBfPAoCXWpdUT7LpooCv_Xjw?e=ZIzakb

## Relevant Manual Pages

https://docs.unity3d.com/Manual/GameObjects.html
https://docs.unity3d.com/Manual/PhysicsOverview.html
https://docs.unity3d.com/Manual/Lights.html

## Skills
* GameObject types (refresher)
* The Transform Component
* Enabling / Disabling GameObjects and Components
* World vs Local Space
* 3D Objects / Meshes / Mesh Filter
* Rendering / Mesh Renderer / Materials
* Lights
* Colliders
* Rigidbodies
* Joints
* The Rectangle Tool
* Sketchfab

## Level
1. Open "First Person Scene"
2. Create a hallway with a floor, walls, and a roof
3. Create a room at the end of the hallway (try to do this *efficiently*)
4. Make a stack of boxes at the end of the hallway, such that your player has to smash through  them, Kool-Aid Man-style
5. Build a swinging pendulum that does the same

## Bosses

### Bowser
A game designer sends you an email for a game element with this story: 
Your character walks down a long hallway into a room. They see shadows on the walls. On the floor is text telling them to "stand here" and a dot on the floor. When they stand there, the shadows resolve into text that gives them a clue to a puzzle on how to leave the room.

Special conditions: in the Scene (and therefore the start of the Game), there is no Light Object in the room with the shadows (nor a light object near enough to cast any shadows); how is it your character can see shadows on the walls?

Puzzle suggestion: one of the walls is a "false" wall.

### Hornet
Make the room above more elaborate. The character needs to move objects around to reveal certain things.
You will need OnTriggerEnter(), and OnTriggerExit()

### Demon of Hatred
Do the above challenges, but build it all with the ProBuider package instead of primitives.

Add in a new game element of your choosing.
