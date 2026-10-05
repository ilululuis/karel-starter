# Karel the Robot

This project contains my Karel work for COSC 10001 at TCU. I use Java to guide a robot around a grid, avoid walls, and collect or place beepers.

## How to run it

Open the project folder in IntelliJ, open `MyKarel.java`, and click the green ▶ button.

Load worlds/LuisStaircase.w, then press **Start**. Karel collects four beepers and finishes at (5,5).

You can also run `run.ps1` on Windows or `bash run.sh` on macOS from the project folder.

## What I learned

- Karel can turn right by calling `turnLeft()` three times.
- The order of commands matters: Karel follows each instruction exactly, even if it sends the robot into a wall.
- Slowing down the robot helps me spot where my instructions go wrong.