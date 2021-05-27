# ComputerCraftGui
Gui api for Computer Craft minecraft mod. 

Check example for a script example but heres all the stuff you can do.

**Import things to have in your script**
There is 1 thing you need in your script for this to work.
```
gui.screenCheck() --Checks if any buttons were clicked. I can not stress enough that this is the most import function. Keep it in a loop.
```

**Labels**
```
gui.addLabel("Text", 1) --Adds text to the screen repeating 1 time. Result "Text"
gui.addLabel("Text", 5) --Adds text to the screen repeating 5 time. Result "TextTextTextTextText"
```

**Spacers**
```
gui.addSpacer() --Adds a empty spot between the item befor it and after it.
```

**Buttons**
```
gui.addButton("Text", CallbackFunction) --Adds a button to the screen that you can click with right mouse button. When clicked it calls the callbackfunction you gave it.
```

**Toggles**
```
gui.addToggle("Text", CallbackFunction) --Make sure that the callback function has 1 parameter. It will call that function with the parameter of either true or false.
```

**Screen Reseting**
```
gui.screenReset() --Resets the screen
```

**Settings**
```
gui.settings(fontSize) --Changes the font size. Keep it between 0.5-5 to not have any errors.
```

More to come in later api updates such as.
- [X] Check boxes / Toggles
- [ ] Text input
- [ ] Sliders
- [ ] More settings
- [ ] Images for gui and background
