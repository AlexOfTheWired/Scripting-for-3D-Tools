# WEEK 1 HOMEWORK

#### 1. What version of Python is being used in your version of Maya?

#### 2. Convert the following MEL statements to Python:
* polyCylinder -h 3 -r 1 -sc 2 -ch 1;
* polySphere -r 3 -sx 8 -sy 8 -ch 1;
* polyTorus -r 1 -sr 0.5 -tw 5 -sx 20 -sy 20 -ch 1;
* polyCube -w 9 -h 9 -d 9 -sx 3 -sy 3 -sz 3 -ch 1;

#### 3. If you run this code (in Python):
* #### the_answer = “42”
  * What type of variable is the_answer?
  * What Python command can you run to confirm this?

#### 4. Most Maya commands have these three modes: create, query, and edit. Explain what each means.
* Create
* Query
* Edit 

#### 5. For the following list: my_list = [2, 3, 7, 8, 9]
  * What is the value of my_list[1]?
  * What is the value of my_list[-1]?
  * What is the value of my_list[:-1]?
  * What is the value of my_list[::-1]?
  * What is the value of my_list[1:-1]?

#### 6. Reformat the print statement to use % string formatting:

    a = 5
    b = 3
    c = pow(a, b)
    print(str(a) + “ to the “ + str(b) + “ power is “ + str(c))

#### 7. Write a short Python script that does the following:

  1. Create a sphere
  1. Create a locator
  1. Connect the locator Y-translate attribute to the sphere scale (Hint: use the connectAttr() command.)
