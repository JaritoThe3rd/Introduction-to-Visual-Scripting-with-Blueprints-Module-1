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


<img width="1966" height="1013" alt="image" src="https://github.com/user-attachments/assets/50de7ae6-14f3-425a-ac7b-8c9cbd75182f" />


<img width="878" height="377" alt="image" src="https://github.com/user-attachments/assets/41bd9eaf-cd3a-4bdc-b26d-176549a3aa62" />


<img width="1234" height="658" alt="image" src="https://github.com/user-attachments/assets/2f4f1cdd-4ebc-4d72-ba9f-cbd04a2ed2c4" />


By the time you added a cube and a box collision then setting the Overlap blueprint to print string "Overlapped" then you just made a pressure plate.


<img width="3439" height="1340" alt="image" src="https://github.com/user-attachments/assets/92778f92-61d5-4836-b14c-355c5f937ab7" />


Creating a Child Class
Basically transferring your settings such as viewport meshes and event graphs into another blueprint actor. Except you're not be able to make changes to the original.


<img width="3439" height="1370" alt="image" src="https://github.com/user-attachments/assets/f445222c-8361-4847-b746-f800db9ce244" />


The new orange blueprint basically calls to the parent event from the original blueprint actor class.


<img width="3432" height="1353" alt="image" src="https://github.com/user-attachments/assets/f0a01eab-eb89-4a0a-b7a4-6e4e909e1967" />


<img width="3418" height="1061" alt="image" src="https://github.com/user-attachments/assets/e22d722d-2b79-4cdd-a64f-374cfda826e9" />


<img width="2738" height="1033" alt="image" src="https://github.com/user-attachments/assets/dbe1a229-ef2d-4615-9111-4df36a20cf30" />


By the time you walk past both the parent and child blueprint classes. Then you will activate their print strings too.


<img width="1294" height="659" alt="image" src="https://github.com/user-attachments/assets/a12c78ae-2cc5-4f7f-8dc2-fa8430545f97" />


<img width="1895" height="1034" alt="image" src="https://github.com/user-attachments/assets/8b37b7f1-b6e1-4b15-90a2-f896230b668e" />


Flow Control
Basically code syntax of blueprints


<img width="1882" height="821" alt="image" src="https://github.com/user-attachments/assets/7c4e5aa6-1b29-4c82-b8aa-2154a6ccb128" />


<img width="1911" height="576" alt="image" src="https://github.com/user-attachments/assets/2064d3f0-2b80-48d4-b765-7ec99420a717" />


<img width="1037" height="560" alt="image" src="https://github.com/user-attachments/assets/6ee22a25-3833-4f7b-b90d-9c206f20e9a2" />


<img width="1220" height="649" alt="image" src="https://github.com/user-attachments/assets/f896153e-c06e-4834-8c1c-cf5ca506faad" />


<img width="3439" height="1349" alt="image" src="https://github.com/user-attachments/assets/1b4dc175-85c1-4fe5-a774-7f7866dc86a8" />


Making a door
Add a Cube component and box collision and make sure that they're separate and not parented to each other.


<img width="524" height="328" alt="image" src="https://github.com/user-attachments/assets/0531e819-439a-456c-a274-a299fd9d21c0" />

Separate


<img width="504" height="319" alt="image" src="https://github.com/user-attachments/assets/60c0622e-1d1d-4328-9a7e-643c8e679d37" />


Parented


<img width="875" height="718" alt="image" src="https://github.com/user-attachments/assets/7cfb5f18-4438-444b-9474-08056d943cdf" />


<img width="512" height="124" alt="image" src="https://github.com/user-attachments/assets/026a85c0-16e9-4127-8a83-8db3574bbbb1" />


Make two new functions for unlocking and closing door.


<img width="824" height="676" alt="image" src="https://github.com/user-attachments/assets/1dce13ee-d940-480b-aab0-d963aa16e669" />



<img width="3387" height="1079" alt="image" src="https://github.com/user-attachments/assets/7e926827-433c-4632-b54c-27569410529c" />



<img width="1309" height="701" alt="image" src="https://github.com/user-attachments/assets/4be4854d-2b4a-4773-9754-6be251d72165" />


<img width="2477" height="1127" alt="image" src="https://github.com/user-attachments/assets/bc83d73f-5fdc-43f1-9ca6-796382962523" />



<img width="1651" height="427" alt="image" src="https://github.com/user-attachments/assets/5456a346-478d-4e7f-83db-9825a0bb5552" />


Using the two custom events called "Open Door" and "Close Door" and connecting into a timeline node to open the door then setting the position with a multiplier to move the door

Eventually using the cube component as a target object to move the location.


<img width="1515" height="264" alt="image" src="https://github.com/user-attachments/assets/9b416b97-79bc-43e2-8eb3-6b7790807108" />


<img width="1582" height="220" alt="image" src="https://github.com/user-attachments/assets/640f6550-7227-4fdc-b0b0-0719e1557b61" />


Using Event overlaps for both opening and closing the door.


<img width="3438" height="1357" alt="image" src="https://github.com/user-attachments/assets/03f78bb5-6a55-4879-b70b-20ee8b27bfb7" />


<img width="1297" height="657" alt="image" src="https://github.com/user-attachments/assets/ada30a4c-9941-4767-ba18-723618ed2325" />


<img width="1371" height="824" alt="image" src="https://github.com/user-attachments/assets/5965aee7-7898-4466-a3a7-a0bf6b6617c2" />


Dragging Variables
"Get" means if you want to read the variable and "Set" means if you want to change it.


<img width="1391" height="531" alt="image" src="https://github.com/user-attachments/assets/e925d003-0550-4f4c-b766-97fc10344af5" />


It is ideal to drag and drop onto the pin.


<img width="1513" height="387" alt="image" src="https://github.com/user-attachments/assets/64f2fcc4-6ebb-4b83-8dc2-611367426b21" />


<img width="979" height="576" alt="image" src="https://github.com/user-attachments/assets/f0c0fe6f-f270-4304-876d-1ac104427497" />


<img width="810" height="482" alt="image" src="https://github.com/user-attachments/assets/2e2332f0-6a9a-4d7e-aaa5-98105f41ca61" />


<img width="1281" height="693" alt="image" src="https://github.com/user-attachments/assets/edfd99a6-12a6-4bf2-aa39-b75bdc9f6eda" />


<img width="1183" height="369" alt="image" src="https://github.com/user-attachments/assets/825c4560-7545-44c9-9363-a74a9a4abf2d" />


<img width="765" height="597" alt="image" src="https://github.com/user-attachments/assets/c13acb49-7ec6-4bcf-a032-bc721eaea8ca" />


<img width="1294" height="652" alt="image" src="https://github.com/user-attachments/assets/52080be4-627e-464a-a51c-47dcf4fce9dd" />


<img width="3439" height="1347" alt="image" src="https://github.com/user-attachments/assets/58a84099-2313-4eb5-915b-b7cd1f9af166" />


So our goal is to add a point light into our cube and making the light status change based on the Unlock and lock status.


<img width="3439" height="1358" alt="image" src="https://github.com/user-attachments/assets/94d44a69-5ac5-45a2-a65c-f7e77eb47e2c" />

Construction Script
Runs its code everytime the object is first created, but this also includes when its first created in the editor.

We tend to use constructions script to see and visualize the code acting upon the actor straight away.


<img width="968" height="769" alt="image" src="https://github.com/user-attachments/assets/edee48bd-1e14-4b8b-bfe1-f41966a5c514" />


<img width="1022" height="514" alt="image" src="https://github.com/user-attachments/assets/130d939c-0994-49a1-8053-e90c0b0b8902" />


Using the select color function is a lot better for readability.


<img width="3430" height="1369" alt="image" src="https://github.com/user-attachments/assets/d50e816e-d3f3-48f2-b72e-03150edce8b3" />


<img width="1581" height="675" alt="image" src="https://github.com/user-attachments/assets/1ed44fba-35e0-4074-b314-ccf8206c3338" />


<img width="1409" height="688" alt="image" src="https://github.com/user-attachments/assets/2ad487d6-3ee5-4fea-98dc-eb4a2324c437" />


<img width="1346" height="661" alt="image" src="https://github.com/user-attachments/assets/14e76ceb-aa8f-4ba9-8259-a2322e3aaae3" />


<img width="993" height="849" alt="image" src="https://github.com/user-attachments/assets/b8ada67c-f3de-4f21-9402-57f08b1cb1a7" />


Making a button that it looks like its being pressed by adding the cube actor and connecting into Set Relative Location to make it looked pressed. Then resetting it, but we will encounter infinite loop.


<img width="2194" height="1028" alt="image" src="https://github.com/user-attachments/assets/f019b8a7-b74c-42a5-9bbe-ba17e602e748" />


Because our box collision is attached to our cube.


<img width="897" height="573" alt="image" src="https://github.com/user-attachments/assets/06652030-cb30-46f0-a1cc-634e7e1637a9" />


We need to detach the box collision from our cube.


<img width="1218" height="671" alt="image" src="https://github.com/user-attachments/assets/91832316-588d-4720-8532-49bb3dd4043d" />


<img width="1595" height="519" alt="image" src="https://github.com/user-attachments/assets/e3a457d4-8566-4ebc-a3c6-0f7219608303" />

Adding these functions so we can add a timer before the door is locked.


<img width="388" height="377" alt="image" src="https://github.com/user-attachments/assets/25a8a673-4f1e-4143-b505-03ffe361be73" />


<img width="763" height="373" alt="image" src="https://github.com/user-attachments/assets/0bd7d4a4-219e-466f-afdd-e24cdfc3be4c" />


<img width="943" height="621" alt="image" src="https://github.com/user-attachments/assets/62017c00-654c-48b2-a79d-be53fd74943b" />


We don't want ButtonUntriggered to be called out so delete the Call On Button Triggered.


<img width="2066" height="1128" alt="image" src="https://github.com/user-attachments/assets/8fb78f34-51ca-4182-a3b7-329b9f5f1a4f" />


So we can change the variable in the editor enable instance editable


<img width="3428" height="1318" alt="image" src="https://github.com/user-attachments/assets/bd46e050-7765-48ad-a620-2d6e9c4dc50b" />


Make sure the timer blueprints are on the ButtonUntriggered that was wrong that we placed it in the ButtonTriggered.

<img width="1224" height="636" alt="image" src="https://github.com/user-attachments/assets/3fc77802-c382-4149-a373-cfa0f551a419" />


<img width="737" height="803" alt="image" src="https://github.com/user-attachments/assets/db26fad9-7953-44b7-9def-2c8628ee392b" />


<img width="737" height="363" alt="image" src="https://github.com/user-attachments/assets/1aa68759-0fb8-4732-9e84-a1336af7eaea" />


<img width="710" height="442" alt="image" src="https://github.com/user-attachments/assets/0528f8da-1ffa-4d23-84bd-6369bb11846f" />


<img width="714" height="419" alt="image" src="https://github.com/user-attachments/assets/152ca0df-1ac4-4b86-8d68-f4dd56b4d825" />


<img width="759" height="610" alt="image" src="https://github.com/user-attachments/assets/13bb739e-aaec-4f8e-a0fb-3025966f5d30" />


<img width="3360" height="1235" alt="image" src="https://github.com/user-attachments/assets/60904f03-d7ca-418d-893c-e22b92ef841f" />


<img width="2219" height="1034" alt="image" src="https://github.com/user-attachments/assets/d826a306-9220-4a62-95c8-cea57daf8a5f" />


<img width="1569" height="1102" alt="image" src="https://github.com/user-attachments/assets/91420402-b7cb-4119-b121-5dab479d99f2" />
