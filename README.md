# Foundations of Computer Science Lab02

Your goal is to recreate this program from the sample code provided:
- <http://homer.stuy.edu/~dw/netlogo/lab02_obf.html>

### Instructions
At the end of this file, you will see a large code block. It contains all the instructions for this assignment. You should:
- Copy the code into a new NetLogo program.
- In NetLogo, fill in the procedures and add the required interface elements.
- When done, save the file as __lab02.nlogo__, and upload the entire file to this repository.

```
; For this assignment, you will need to create procedures
; and interface elements.
; Use this example as your guide:
; http://homer.stuy.edu/~dw/netlogo/lab02_obf.html

;=========================================
; Buttons
;
; Most procedures should have a corresponding button.
; If the button is meant to be a forever button it
; will be mentioned above the procedure.
;
; Add buttons for the pend-down and pen-up commands.
; These will be helpful for testing your code.

;=========================================
; Sliders
; numTurtles: range should be [1, 100] with all
; integers in that range available.
;
; stepSize: range should be [0.0, 5.0] possible values
; should be 0.0, 0.1, 0.2, 0.3 0.4 ...
;=========================================

;=========================================
;Procedures

;=========================================
; setupRow (normal button)
; Clear the screen.
; Make enough turtles so there is one per
; patch along the y axis.
; Each turtle should be on the left side of
; the world, on its own patch.
; Each turtle should face right.
to setupRow

end

;=========================================
; stamp4 (normal button)
; A turtle should move forward 1 step.
; Every 4 steps, a turtle should leave a
; stamp of itself.
to stamp4

end

;=========================================
; wiggle (no button)
; This procedure is to create random turtle movement.
; It should be used in some of the methods below.
; When you have created the stepSize slider, modify
; this code so the turtle moves forward by that amount.
to wiggle
  rt random 360
  fd 1
end

;=========================================
; trap (forever button)
; If a turtle is within a square bound by
; 10 and -10 in both x and y, it move randomly.
; If it goes outside that range, is should be
; sent back to the origin.
to trap

end

;=========================================
; setup (normal button)
; clear the screen
; make numTurtles (slider) turtles
to setup

end


;=========================================
; slant (forever button)
; A turtle should move randomly.
; pick 2 colors, turtles should be one
; of those 2 colors based on if they are
; above or below a diagonal going from
; the bottom-left to top-right corner of the world.
to slant

end

;=========================================
; diagonal (forever button)
; A turtle should move randomly.
; pick 2 colors, turtles should be one
; of those 2 colors based on their position
; in the world. Use the sample program linked
; above to see this pattern.
to diagonal

end
```
