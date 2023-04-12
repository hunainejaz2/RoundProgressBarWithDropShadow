# RoundProgressBarWithDropShadow
Create Round Progress Bar with inner side drop shadow

1-- Create a new drawable Resourse file in drawable folder.

2-- Select the parent root Layer-list. Layer-list can hold multiple items in it.

3-- Now add 2 items tags in Layer-list 

4-- Add Id Attribute in 1st item and give value to id attribute "@android:id/Background". its means that you mention that this item is background layer of progress bar

5-- Also add Id attribute in 2nd item than give value to id attribute @android:id/progress".its means that you mention that this item is progress in progress bar

6-- Now add the "Shape" Tag in Background item.
    In shape tag add "shape" attribute and give "ring" shape for round shape of progress bar.
    Now add "ThicknessRatio" attribute to shape tag.ThicknessRatio can adjust Ratio of radius of Circle.
    Than add last attribute which is "use Level".Use Level can get boolean value.if value is true its mean that the shape can move as the value of progress     increase.
    
7-- Add "Gradient" tag in shape.
    
