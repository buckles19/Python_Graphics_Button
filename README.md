# Python_Graphics_Button
A button class that can be used with the Graphics Python module

Important:
  
  The graphics module must be called in your main function for the code to work!

Current Features:

  Button()
  
    asks for two points, box and outline color, text, text color and size, and the name of the WinGraph function in your code   
    
  getCenter()
  
    returns the coordinates of the center of the button
    
  click()
  
    allows the button to be clicked by the user and returns a True value if clicked on and a False value if clicked elsewhere
    
  check()
  
    allows the button to be checked for a click from the user and returns a True value if clicked on and a False value if clicked elsewhere
    
  movingClick()
  
    asks for number of clicks allowed and then moves the button to wherever the mouse is clicked in the window
    
  move()
  
    moves the button a set distance according to the two values requested
    
  undraw()
  
    undraws the button
    
  resetColor()
  
    changes color of the button
    
  resetLinecolor()
  
    changes the color of the outline of the button
    
  resetTextcolor()
  
    changes the color of the text
    
  resetTextsize()
  
    chnages the size of the text on the button
    
  getValues()
  
    returns a list of all True and False values that the button has returned
