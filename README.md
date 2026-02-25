# GDIM32 In Class Activities
## Week 1 In-class activity

### Activity 1

Get started on the minigame as soon as possible, don't procrastinate

### Activity 2
 - 10
 - 2
 - prints "hello world" in the console every frame.
 - Update and debug logs are usable in Monobehavior. ??? should be replaced with Monobehavior.
 - "x = 10" is printed
 - The highlighted areas are the arguments/parameters. 10 is passed into the method
 - In line 5, it should be _playerTransform.Translate(_direction) because Transform is already defined
 - Change Transform to _playerTransform


### Activity 3

https://docs.google.com/document/d/1UQTlTMUv7OoSRXdfaYn3iWpCgYABL-kNvOKmFYxCaUk/edit?usp=sharing


## Week 2 In-class activity

### Activity 1
![W-2 Inclass activity Drawing](https://github.com/user-attachments/assets/947dcd4c-746d-4594-8b1d-4f250ce23e8a)

### Activity 2
https://github.com/UCI-GDIM32-W25/mg2-celotolosa/commits/main/

In this push, I created all the needed objects within the game and created a fully functioning jump mechanic in the PLayer script. I need to figure out how to make the coins randomly spawn and move across the screen, while also updating UI text everytime the player collides with a coin. They need to be destroyed when they go off the screen as well.

## Week 3 In-class activity

### Activity 0-2:
Kai Meng

### Activity 3:

![gdim32mg3breakdown](https://github.com/user-attachments/assets/f8f0d91d-a57d-4dd0-8ce8-2e37cc73e8d8)

## Week 4 In-class activity

### Activity 0:
Eric Wei

When multiple Locator objects are added to the scene, only one is kept because it is a singleton. 

### Activity 2: MG4 break-down
![Github](https://github.com/user-attachments/assets/3f7e9225-47af-4500-b8b7-914740a166c4)

## Week 5 In-class activity

### Activity 1: 

I honestly think the design of the interfaces and abstract classes are a bit confusing to me, I feel like interfaces are for much more unrelated objects and defined while abstract classes use shared behaviour. 

### Activity 2:

The InventoryUI is the view. The PlayerW5Demo2 is the controller. The EnemyStats and ItemW5Demo2 classes are the model.

### Activity 3:

Scenario 1: The project includes inheritance and polymorphism that might have the buttons as a parent class, and the different buttons that add separate points as child classes. As a FSM, different button types can change the state depending on the button that's instantiated. This can track whether the player needs to hit a combo, click or hold down on the buttons that could change the amount of points received.

### Activity 4:

[GDIM 32 Highly Entropic Beings](https://docs.google.com/document/d/1IXMcedZDubU3jHOIg-ZRwtj0N-xMFaV7MpOOSQTA65Q/edit?tab=t.0) 

## Week 6 In-class activity

### Activity 1:

Notes: We can use the profiler (Window -> Analysis -> Profiler) to check what methods are executing and look at how long it's taking said  method's to execute. Additionally, there's no need for a polygon collider if our game has a lot of detail. Locator makes it easier to reference a single component such as the player, so there aren't as many references in other classes, and no need for GetComponent as much.

### Activity 2:

Attendance: Marcelo Tolosa, Nathan Hernandez, Kai Meng

## Week 7 In-class activity

### Activity 1:

Raycast returns a boolean, and code will run inside brackets if true is returned. Difference between SphereCast and RayCast, spheres can provide more information about what's in front of you as opposed to a singular line of sight.

### Activity 2: 

Nathan Hernandez, Kai Meng

### Activity 3:

![GDIM 32 Final Breakdown](https://github.com/user-attachments/assets/3ca5bb78-5f17-4281-bf2f-bac2582042ea)


### Activity 4:

Tasks are assigned via Trello

### Activity 5: 

Commit made in class: https://github.com/lindenreid/GDIM32-Final/commit/e100e6fe5fff93e9c6c886e59c0b2cf93d4f5bf6
Created an NPC script and two separate colliders to detect when an NPC would be in range. I discussed with Kai how I would go about detectint NPC's for dialogue and interaction.

## Week 8 In-class activity

### Activity 1:

How to find out what Rendering Pipeline I'm using. Hit edit > Project Settings > Graphics. How to set up post-processing in built-in pipeline. First, download the Post Processing package from the Unity registry. Open the package manager under Window > Package Manager, then navigate to the Unity Registry section and install the Post Processing package.

### Activity 2:

Kai Meng, Nathan Hernandez

### Activity 3:

Playtest notes: I did not say anything to the playtesters at first, and they did not know that you could charge your character's jump. After telling them, they found the mechanic to be difficult yet enjoyable. While the movement mechanic is still WIP, it seems to be working well. Around 50% of the playtesters' jumps resulted in their death, but they gradually decreased their margin of error. They encountered a bug where the player can indefinitely suspend themselves in midair if colliding with the side of a platform. Playtesters suggested that the player should be able to move while falling -- it would make the game more forgiving.

### Activity 4:

I'm going to work on transferring all of the playerinteract code into the player class, and then create an NPC parent class, with child npc classes that will inherit methods

### Activity 5:

Commit made in class: ([Commit ]https://github.com/lindenreid/GDIM32-Final/commit/aa3f597a02746f79fb628b192f13323e39931477) I made a new Parent NPC class with two child classes, QuestNPC and DialogueNPC. Also implemented the correct logic for player interaction in the player class. Deleted the playerinteract class.
