# NightVision
 Pavlov VR - NightVision by KENNITHH, Spin, BravSoldat

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Installation


1. Copy the Content folder into your "/ProjectNameHere/" folder, (NOT this Content inside your Content folder)
2. Open your project and MOVE everything from inside "UGC0000000000" inside your UGC folder
3. Right click the Content folder in editor and press "Fix Up Redirectors"
4. If you have NO Custom PlayerProxy go to Step 7 if you already have a Custom PlayerProxy go to the next Step
5. Open your CustomPlayerProxy, Select File -> Reparent Blueprint and select BP_NVplayerProxy from the list
6. Inside your CustomPlayerProxy, right click "Event Beginplay" and select "Add call to parent Function"
7. Assign your own CustomPlayerProxy OR my BP_NVplayerProxy inside your Pavlov_GameLogic

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
