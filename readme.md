# Hue Boxes

Academy Pittsburgh assignment - recreating page made by Jennifer Dewalt - https://jenniferdewalt.com/technicolor_boxes.html

By hovering the mouse over the central coral block, colored boxes appear at random.
My version allows user to select between random color generator or blue tone colors. 

![Image of Hue Boxes](https://github.com/reg710/Hue-Boxes/blob/main/HueBoxes-SampleImage.png)

STILL TO DO:
- Create header with short explanation
- Add additional color option buttons - try different approach than blue array method
- Attempt rainbow option, where the container box has ROYGBIV columns that change only within their color
- Simplify functions where possible 

PROJECT NOTES:
- Try to limit the color to only blue tones
    -- Did this by creating an array of select blue(ish) hex values 
- Add a glow when color changes
    -- Did this by adding hover box shadow in white
- Limit boxes to within a fixed square in the middle of the page?
- Have the boxes a fixed size so they don't stretch when you resize
    -- Did these by creating a container box that was sized to match number of divs, with no padding/margin
- Buttons that when you click can pick different changing colors 
    --Added bootstrap styled buttons, I like that when a button is clicked it stays highlighted!


