# SM-ShowTriggers-Redux
A rework of the original showtrigger plugin by ici. This version allows more customization of which brushes are visible.

if you want to modify to add more to the list:
- add the brushes to the enum list
- add to string array in same exact order as the enum
- add case to CheckBrushes()
- create a hookST_* function for the brush
