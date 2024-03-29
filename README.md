# Project 2_Group 12

![Main](https://user-images.githubusercontent.com/55362861/99926443-59d3b600-2d07-11eb-8ca1-970d9480a630.JPG)

## The Warrior Prince
This game will be a multilevel game in which the player will be tested on their ability of fast decision making. The first level, player will have different weapons and will try 
to defeat all the enemies within a terrain. After defeating the enemies, they shall enter the second level; in this level they shall defeat various species of enemy in a room. In 
this level they not only have to kill the enemies but would also need to kill their "Boss" in a castle like structure.

## Project Objective 
The main objective of this project was to make a VR game to help people make prompt decisions. To work as a team and overcome the obstacles.
## Initial Sketch

![WhatsApp Image 2020-11-01 at 5 52 22 PM](https://user-images.githubusercontent.com/56169161/97818950-1edfe480-1c6b-11eb-945b-1480b0f9aba0.jpeg)

![all levels](https://user-images.githubusercontent.com/56169161/97818648-2a321080-1c69-11eb-891b-41c92f0f54c7.jpeg)

## Implementations :

As we did not have any VR devices we decided to proceed with a First Person Shooter (FPS) game. But this game can be easily extended on a VR device.

### Instructions :

The game has a 3 Different scenes integrated together. The First scene is a Main menu scene which has Play, Quit and More as options. When the player clicks More Options, they will be instructed on how they can play the game, as shown in below Screenshot.
![Instruct](https://user-images.githubusercontent.com/55362861/99926439-593b1f80-2d07-11eb-8a23-e6ee814f4b1e.JPG)

The Play button will take them to the Main game, i.e. Level 1, the quit button will exit the Player out of the game completely.
### Level 1

We decided to go with a terrain for our first level, we imported a pre built asset from Unity store (links for the assets are provided below). We did this to save time, we then 
made Prefabs for our Emenies and Player, spawned the enemies all over the scene. As we need to present this game within 3 minutes we decided to have a 90 seconds timer for level  1. If the Player survives the first 90 seconds of the game, they will proceed to level 2.

![Level1_Scene](https://user-images.githubusercontent.com/55362861/99926441-59d3b600-2d07-11eb-998f-57469652910a.JPG)

### Level 2
We decided to go with a temple like structure for our second level, We imported a pre built asset but unfortunately it did not have all the models and a proper scene so we had 
to build the second level from scratch by using the models and assets in the Unity Assets stores. This level not only had two different types of enemy but also had a Main boss 
enemy. The player is supposed to kill all the enemies along with the main boss. 

![Level2 scene](https://user-images.githubusercontent.com/55362861/99926488-8687cd80-2d07-11eb-8796-71907af8744a.JPG)

![Assault rifle](https://user-images.githubusercontent.com/55362861/99926486-85ef3700-2d07-11eb-9b17-39ec45e915a5.JPG)
![Level1_Revolver](https://user-images.githubusercontent.com/55362861/99926440-593b1f80-2d07-11eb-96fa-4fbbf16f9c15.JPG)
![Level2 scene_1](https://user-images.githubusercontent.com/55362861/99926489-8687cd80-2d07-11eb-8b65-4af0d4ef37d1.JPG)
![zom](https://user-images.githubusercontent.com/55362861/100173242-b2ce5600-2e8f-11eb-84f5-07e8489c2f89.JPG)


![crab_monster](https://user-images.githubusercontent.com/55362861/99926515-a0291500-2d07-11eb-9715-25b2f7da8bc2.JPG)
![Mainboss](https://user-images.githubusercontent.com/55362861/99926516-a0291500-2d07-11eb-973e-09ac616371c3.JPG)

When the Player losses the game the below page will be displayed on the screen.

![endpage](https://user-images.githubusercontent.com/55362861/99926778-6efd1480-2d08-11eb-8509-27ef12b11ca3.JPG)

## Scripts
### Player Scripts
The weapon script is to select the different weapons within the game.

![weapon script](https://user-images.githubusercontent.com/56169161/99928774-306b5800-2d10-11eb-894b-40a2e8bc5731.JPG)

This script is for the Player attack,

![fire script](https://user-images.githubusercontent.com/56169161/99928773-306b5800-2d10-11eb-86df-ff8133e28902.JPG)

### Enemy Scripts

The below script is the enemy movement script, which helps the Different enemies have movements like run, walk and attack and spawning the enemies.

![enemy movement script](https://user-images.githubusercontent.com/56169161/99928771-2fd2c180-2d10-11eb-9f6d-2629d6d4545c.JPG)

![es](https://user-images.githubusercontent.com/56169161/99928772-2fd2c180-2d10-11eb-8726-6064748c6850.JPG)


## Game Demo
[Play Game?](https://simmer.io/@zoeee/vr-group12)

[Video Link](https://youtu.be/zX1BUXQcuXE)

[Drive Link](https://drive.google.com/drive/folders/1kg0o7La-kHzNU8Nkm_ou7Gdnw0-QYMQX?usp=sharing)

## Assets
[Level 1](https://assetstore.unity.com/packages/3d/environments/nature-starter-kit-2-52977)

[Level 2](https://assetstore.unity.com/packages/3d/environments/ancient-jungle-temple-demo-123179)

[Main Boss](https://assetstore.unity.com/packages/3d/characters/insectoid-crab-monster-lurker-of-the-shores-20-animations-107223)

## Useful Links
We used this tutorial to learn how to implement the FPS movements and controls

[Youtube link](https://www.youtube.com/watch?v=_QajrabyTJc)

We went through the below tutorial for weapon control

[Youtube link](https://www.youtube.com/watch?v=THnivyG0Mvo)

## Responsibility
Durga Prasad : Implementing, designing and Testing Level 1 and Main menu. Integrating the level as a complete project, Report.

Zoya Shaikh : Implementing, designing and Testing Level 2 and the end page. Integrating the level as a complete project, Report.
