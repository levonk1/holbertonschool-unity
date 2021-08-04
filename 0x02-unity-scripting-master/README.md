# 0x02. Unity - Scripting

![alt text](https://docs.unity3d.com/uploads/Main/ScriptingIntroPic.jpg)

## Learning Objectives

General

- What are scripts in Unity and how are they created and used
- How to control GameObjects with scripts
- What is an event function and how are the most common ones used
- How to create and destroy GameObjects within scripts
- How to use namespaces to organize classes
- What are attributes and how to use them
- How to use Debug.Log()
- What is a vector

## Tasks

### 0. Ready player One
Inside the maze scene, create a Sphere GameObject named Player with a Rigidbody component.

- Position: (23, 1.2, 16)
- Scale (2, 2, 2)

### 1. Bust a Move
Create a directory Scripts. In this directory, create a new C# script called PlayerController.cs. Attach this script to the Player object. Within this script, update the Start() and FixedUpdate() functions to allow the Player to move when either the WASD or arrow keys are pressed

### 2. Camera Ready
Move the Main Camera to position (22, 26, 7). Create a new C# script in the Scripts directory called CameraController.cs.

### 3. Insert Coin
Create a new Cylinder GameObject named Coin.

### 4. Coin Collecting
Create a new C# script called Rotator.cs and attach it to Coin.

### 5. Danger Zone
Create a new Plane GameObject named Trap.

### 6. You've activated my trapcard
Add a new public int health variable to your PlayerController.cs script. Set the initial value of health to 5.

### 7. The Finish Line
Create a new Plane GameObject named Goal.

### 8. Goalllll
In PlayerController.cs, add to the existing void OnTriggerEnter(Collider other) function

![Alt text](https://github.com/Ken-Mens/0x02-unity-scripting/blob/master/Unity_Script.png)


### 9. Game Over
Create an Update() function within PlayerController.cs.
