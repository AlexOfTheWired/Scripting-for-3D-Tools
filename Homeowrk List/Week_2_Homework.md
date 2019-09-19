# WEEK 2 HOMEOWRK #

### The goal of this assignment is for you to become familiar with using variables, lists, and functions to do the majority of the work in your code.


#### 1. Write a function called rename_obj that takes a string as an argument to rename a selected Maya object.
(Hint: use my_selection = maya.cmds.ls(selection=True) This assigns any selected objects in the scene to a list called “my_selection”.)


#### 2. Explain what a for loop is, and write a function that uses it to print the name of each object in a list.####
(Hint: This list of objects could be called “my_selection”)


#### 3. Explain what the range command does, and write a function that uses it to add the word "node" to a list containing the numbers 0 through 9: ["1","2","3","4","5","6","7","8","9"] Hint: the len() function will be helpful.


#### 4. Write a function called print_parents that takes a list of Maya objects as an arguments and prints each node and its parent node.
(Hint: use listRelatives command.)


* #### Create four objects in the scene. Cube, Sphere, Cylinder, Torus.
* #### Parent Torus under Cylinder. Then parent Cylinder under Sphere. Then parent Sphere under Cube.
Use the example hierarchy below for the objects required for the print_parent function.
( Torus > Cylinder > Sphere > Cube)


#### 5. Format a print statement using % notation that list the selected object and all of its parent nodes.
(eg: “Selected Geometry: , Parents: ”)


## ADVANCED (Optional)

#### 6. Write a function called get_poly_info that takes a Maya node as an argument and returns a dictionary with keys vertex, edge, and face and values are the number of each in that piece of geometry. #### 
(Hint: the Maya command that gives you that information is called polyEvaluate.)

#### 6. Write a function called find_center that takes a Maya geometry node as an argument. Since you should know how to get the number of vertices in a mesh, use this number to create a for range loop to find the average/center position of the mesh. #### 
(Hint: xform(<geom.vertex>, q=True, ws=True, t=True))

#### 7. Using list comprehension, create a Python list that consists of all meshes with more than 100 faces. #### 
(Hint: use the ls command type arg to get the meshes and the polyEvaluate to get the number of faces)
