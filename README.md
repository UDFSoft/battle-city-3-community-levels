# Battle City 3 — Official Example Levels


[Official page](https://battlecity.udfsoft.com/)


This repository contains the **official example levels** for **Battle City 3**.  
These levels demonstrate the structure, format, and features of Battle City 3 maps.  
Community-created levels may also be added in the future as optional contributions.

## 📂 Level Format (JSON)

Levels are stored in JSON format.  
Below is a simplified example of a typical level:

```json
{
  "name": "First classic level",
  "mapVersion": 1,
  "author": "UDFSoft.com",
  "levelType": 0,
  "countOfKilledEnemies": 10,
  "fixedCameraFlag": true,

  "hero": { "name": "Hero", "position": { "x": -2.52, "y": -6.47, "z": -1.0 } },
  "finish": { "name": "NetworkFinish", "position": { "x": -0.01, "y": 2.68, "z": -1.0 } },
  "eagle": { "name": "Eagle", "position": { "x": 0.0, "y": -6.5, "z":  0.0 } },

  "correctBrickWalls": [
    { "name": "CorrectBrickWallBlock (16)", "position": { "x": -1.6, "y": 3.5, "z": 0.0 } }
    // ...
  ],

  "brickWalls": [],
  "smallBrickWalls": []
}

```

