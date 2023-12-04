There is a spelling mistake bug when creating a project and selecting a blank project. Instead of blank it says black. The bug can be found when at first log in to GitLab, then navigate to the Project page. At there select New project and the bug is shown.
   
The bug is a spelling mistake and it does not prevent the program from running. Instead of blank = black. See the picture:

image(![Alt text][def2])

It should be instead of black = blank. See the picture:
image(![Alt text][def])

The typo in the text code should be fixed.

/label ~bug ~reproduced ~needs-investigation 
/cc @project-manager 
/assign @qa-tester

Bug priority is minor.


[def]: ../Image/Bug_Screenshot.png
[def2]: ../Image/Bug_Project_create_blank.png