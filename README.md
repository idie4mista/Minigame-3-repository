1. The Default value for all floats and ints is 0. Bools default to false, and strings default to nothing, aka ""

2.The Update() method is called every frame. The body within the method is called every frame, meaning the code inside runs every framel; Every frame, the Update() method runs.
Update() is not called by you; it is called by Unity. You have to define the Update() method first and the unity will know and run Method() every frame for you. 

3. In KickWeapon, it checks every frame (hence the Update() method) if the timer had run out. If it did, then it deactivates the kick script.
In TimerText, It first checks (every frame) if the game had ended. if it did, display the text "Game Over!". If it didn't, then switch the display text to whatever the current time is
