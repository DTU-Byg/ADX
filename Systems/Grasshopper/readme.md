# Analysis
Introduction 

In front of you is a series of tests that can be done as part of the building design process. 
The main goal is to allow these analyzes to constitute an optimization process at an early stage,and during the process, not only when the model is far advanced.

please notice that each analysis has its own modification, settings that need to calibrated before use.
We advise you to execute each code individually in order to avoid overloading the testing process

 
**Acoustics** 

This script focuses on obtaining values ​​that help determine if the materials selected for a particular space 
are appropriate for the type of activity desired.

1.Download from "FOOD4RHINO"- PachyDerm_Acoustic plug in for Grasshopper and rhino
2. Pick a spcae where you want to test this area and make sure it is opened in rhino program
3. Divied the different surfaces into mateirals, by  seperting to layers.
4. open in rhino PachyDerm_Acoustic ( make sure you have installed this plug-in prior to this step, see number 1) 
5. Define each layer a matireal with Absorption,scattering,Transparency values.
6. when finished press "save Material"
7. Indisde the script follow the notes and guidlines 
8. after setting all the inputs, enable analyze component
9. review result.
10. make adjustments accordingly

**Sun light hours** 
This script can be used in the early design process, and for evaluation of of the obtained direct sunlight in the different rooms. 
According DGNB 2020 manual it is important to have at least 2 hours of direct sunlight in at least one room for dwellings. 

1. Download the script and connect windows to the honeybee zone defined windows 
2. Connect the honeybee zone - walls and context (if available)
3. Make sure that the right epw. file is connected. 
4. Make sure that the model units is in milimeters - or scale the different parameters to obtain a resonable grid and fondsize.
5. Click the red marked Toggle to True and run the simulation.
6. The results will be shown as a colourplot on the windows both in Rhino and Revit with a color ledgend from 0 to >5 hours which corresponds both to the DGNB 16 and 20 manual
7. 
