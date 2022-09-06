# escape-room-game

Two game modes:  
    1) secret_object.py  
    2) escape-room.py  

----------------------------
1) Secret Object Game
----------------------------
Required Files: "secret_layout.txt"  
Other Files: "floor_plan.png"  

Find the secret object to win the game  
How to play:  
    1. Run "secret_object.py"  
    2. Follow the instructions and input values into the terminal  
    3. Type "quit" at anytime to end the game  
    4. The game will automatically terminate upon finding the secret object  

The conditions have been randomly generated. This includes the:  
    1. Starting location  
    2. Room with the secret object  
    3. Secret object  

The connected rooms are fixed and have not been randomly generated.  
Check the "floor_plan.png" file for more information about the room layouts.  

New rooms and objects can be added into the game without affecting the gameplay.  
The code will automatically update these new additions.  

----------------------------
2) Escape Room Game
----------------------------
Required Files: "escape_layout.txt", "responses.txt"  
Other Files: "floor_plan.png"  

Find the exit and leave the building to win the game  
Advanced version of the Secret Object Game  
The starting location will be fixed  
Extra interactive items will be added to the objects in the game  
Certain objects will be "locked" and will require interaction with other items (e.g. keys)  
Inventory list will be created to store and check for these items  
