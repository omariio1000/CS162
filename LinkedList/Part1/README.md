Linked List

You will be creating the first part of a student list program that uses linked lists. You must create a Node class. It will include a pointer to a Student class (not struct).

Variables required: Student*, Node*

Functions required:

Node* getNext() //get next Node pointer (10 points)

Student* getStudent() //get student pointer (10 points)

void setNext(Node*) //set the next pointer to the corresponding node pointer (10 points)

Node(Student*) //constructor (10 points)

~Node() //destructor (10 points)

Make sure you test and document your project thoroughly! Comments go into the .h file. Your code is going to be given to someone else for the second part of the project.

Turn in the project as a repository with Node.cpp, Node.h, and any other code that is necessary to prove your Node class works. (Main.cpp, Student.cpp, etc.) This url is the one you will turn in for this project. 

Also, create a second repository which only contains Node.h and an object file, Node.o, in place of Node.cpp. (An object file is created by compiling the code the "-c" flag.) This repository is the one you will share with someone else in the second half of the project. MAKE SURE YOU COMPILE THIS IN CYGWIN IN THE LAB. It matters what platform you compile it on. The .cpp can be made anywhere; it's only the .o file that is platform specific.

