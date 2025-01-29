# ARPoly

An educational AR app made in Unity with Vuforia and written in C#. 

App was made for my MSc project: Assessing the viability of use of Augmented Reality in aiding education of primary school children in developing countries. 

## Features

- 4 scenes: MainMenu, Batch1, Batch2, Endgame
- Each batch contains 5 3D models with descriptions
- Models are displayed for two minutes each
- Integrated feedback sounds throughout the app
- Single Game Manager script
- Optional skip button

## Technical Details

- Unity version 2019.1.7f1
- Vuforia version 8.3.8

## Setup Instructions

1. Download the repo and open it in Unity
2. Get a Vuforia license (free license is fine)
3. Navigate to Resources/VuforiaConfiguration
4. Input your license in the appropriate field in the Inspector window

## License Notice

You can download and use the app, but you cannot use the 3D models or the target picture as they are either purchased or custom-made with restricted licenses.

Project site: pkozakdev.com/ar

## Update History

Update 8.9.2019
- Consolidated two Game Managers into single script
- Added optional skip button (wasn't in the original build for a reason)
