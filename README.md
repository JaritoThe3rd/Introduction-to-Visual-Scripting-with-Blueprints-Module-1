# Introduction-to-Visual-Scripting-with-Blueprints-Module-1


<img width="1012" height="497" alt="image" src="https://github.com/user-attachments/assets/36761d8e-c6b1-4188-9186-c3f9ff8ce417" />


<img width="1396" height="758" alt="image" src="https://github.com/user-attachments/assets/32d4ea4d-f612-455d-a4c7-01435b2caf01" />


<img width="1364" height="656" alt="image" src="https://github.com/user-attachments/assets/5e5c99a6-6ab9-4902-9f98-4f54c25137ea" />


<img width="1292" height="643" alt="image" src="https://github.com/user-attachments/assets/fd268901-c63f-472c-9e88-f867730bcd6a" />


<img width="1243" height="651" alt="image" src="https://github.com/user-attachments/assets/961640f0-c960-4d5a-bacc-dfb42613fc7a" />


<img width="1038" height="589" alt="image" src="https://github.com/user-attachments/assets/96977f5d-0996-4469-ab83-d7a3ceeaf5c8" />

This checked box only shows functions that's only available for that specific node.


<img width="1035" height="784" alt="image" src="https://github.com/user-attachments/assets/36fbdbe5-a69d-4ec1-809d-5973c6475002" />


Clicking expand on the node and dragging "Hit Actor" will make it easier to find specific functions that are meant for that node.


<img width="1353" height="653" alt="image" src="https://github.com/user-attachments/assets/467bad20-d60f-4d2d-99e0-017aad7c92db" />


<img width="1435" height="796" alt="image" src="https://github.com/user-attachments/assets/16a17070-d55d-4e74-9ecf-d05f39c6f2ec" />


Pay attention on the Axis on the bottom left corner which tells you where your static mesh is placed once in the real world.


<img width="3428" height="1438" alt="image" src="https://github.com/user-attachments/assets/2620e628-dfef-4ca0-8e17-39c0fcd8e3d5" />


<img width="608" height="169" alt="image" src="https://github.com/user-attachments/assets/526b0e56-98b4-48cc-8a42-64e404bfb792" />


Whenever they mention that the point light and weapon component is childed to that mesh it basically means it is connected to its parent or inside the mesh


<img width="2900" height="936" alt="image" src="https://github.com/user-attachments/assets/db1c0a88-25c9-4471-8321-586b1ab86d45" />


When you're changing the turret it will be considered an instance and it will not change the original state of that blueprint actor (Turret). Each changes within the map would be an instance on its own and not the original at all.


<img width="1352" height="664" alt="image" src="https://github.com/user-attachments/assets/65e27cc2-b11c-4086-acd2-762c1c841a0c" />


<img width="3365" height="1352" alt="image" src="https://github.com/user-attachments/assets/29a914b3-dd40-4281-8685-7bfcc889965c" />


Keep in mind that blueprints and code are actively translating the functions while you're playing in the editor.


But once you packaged the game and that blueprint script running in the background will be gone since it is fully packaged. (Packaged build will run a bit better)


Fun fact: People tend to argue that blueprints are a lot slower compared to C++. But the instructor for Epic games stated that in the early stages of blueprints that was a strong case.


There are elements where it will run better in C++. but for the most part it is negligible. (Most optimizationa are really important on the rendering instead of coding side of things.)


<img width="1855" height="861" alt="image" src="https://github.com/user-attachments/assets/82ee01e0-bea5-4f5e-b9fc-cc4eb498fff6" />


<img width="1462" height="695" alt="image" src="https://github.com/user-attachments/assets/3b00e376-8f6a-402f-9c00-820d22bdcba4" />


<img width="1176" height="419" alt="image" src="https://github.com/user-attachments/assets/a0f8fc1a-9c10-45ab-8e29-24ad13fce92b" />


<img width="1180" height="669" alt="image" src="https://github.com/user-attachments/assets/ec9afae9-7e38-472e-b19b-062f42f1aa7f" />


<img width="1610" height="760" alt="image" src="https://github.com/user-attachments/assets/44d06de2-b385-4068-bf24-ed37811883dd" />


Take advantage of Delay function (When a blueprint has a clock Icon it cannot be inside a function!!!) and print string for testing blueprints.


<img width="1179" height="663" alt="image" src="https://github.com/user-attachments/assets/1fb67269-02d1-46ef-a99d-fed6eecf7194" />


<img width="1319" height="663" alt="image" src="https://github.com/user-attachments/assets/c8866a51-8ead-4d95-aefa-e9fa15109f54" />


<img width="805" height="283" alt="image" src="https://github.com/user-attachments/assets/38c9f80e-0150-4648-ae4b-083d35c6e007" />


The "Event BeginPlay" blueprint start right away when the games starts


<img width="895" height="225" alt="image" src="https://github.com/user-attachments/assets/243013e4-edcf-4f08-99f8-d96373162632" />


The "Event ActorBeginOverlap" is when any other actor overlaps other actors.


<img width="521" height="221" alt="image" src="https://github.com/user-attachments/assets/982002ea-2655-4164-bc87-c2421943b032" />


The "Event Tick" blueprint runs when the game is running at 60 FPS. So does the Event Tick blueprint.



