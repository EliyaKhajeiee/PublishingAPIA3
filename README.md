# PublishingAPIA3
README
Assignment 3 is a play off of both assigment 1 and assigment 2. The actual content of the assignemnt wasn't too long but we connected the user to a DSU server. By going through the C and the 
O commands with create and load a DSU file. The user is able to import more commands to be able to post their contents online to a server. By being connected via a server IP we are able
to either send a post or a bio or both. This comes with some drawbacks as tyhe code doesnt allow you to post a bio thats empty or a post that is empty. The rest of the A2 commands are still
present and are able to be used via the admin command. This codes UI is a little sloppy yet should work with the error testing being perfect for things like the server commands. Similarly 
shown in the the last part of assignment 2 builds upon the first section of assignment 1 by adding new functions that have to do with the O and the C. 
We build upon the last sections and add new commands to the command line prompt with functions E and P. This time importing different modules Profile 
and UI which both have different uses. The profile class and module provided by the professor has many uses like Save_profile, get_posts, and most importantly the
profile __init__ function itself. This is used to save an instance of a class using an object and setting that equal to the class then calling that 
variable to change anything needed. The UI modules stands for user interface and it is the code responsible for acting with the user. It has many 
print and input statements and is the code that stores both my E and my P functions. This edit and print anything the user needs to be inputted 
and adds the variables stored. The user interface asks the user if they want to input either a C or O. Similar to the last assignment the C
command creates a .dsu file in the directed directory and if it already exists it sends the path to the O function which will load the file 
with the user. The rest of the function is similar to what it was in parts 1 and 2 of assignment 1. This program is a longer version and more in-depth version of Assignemnt1Part1. It differs as it takes a user input as opposed to a command line system argument yet does
the same thing as part 1 with the exception of adding 3 new commands. It adds the commands R,D,C which all do different things. The R commands take a user-inputted path and read the contents
inside of the file. If the file doesn't have anything inside of it, it print("EMPTY") showing that the contents of the file are empty. The C command creates a file and takes another user input
with the name of the file that wants to be created along with the path or directory which the user wants to put in there. The last new function is the D function which deletes the file with the extension
.dsu that is given by the user. Similarly, it does the same things as part 1. At the moment the code takes a directory given by the user and gives many options in order to specify what the user wants. The simple option is "L" which prints the contents of the directory 
given by the user. With the L command, you are able to take 4 different options -r, -f, -s, -e. The -r sub-command prints every fire and directory recursively. This is the area I had trouble with
as I was not able to pair -r with other commands without having errors. This will be fixed in part 2 of the assignment. the -f function gives all the files excluding the directories from the given file path.
The -s function takes another user parameter with a full example.exe file path and prints all the matches with that file path in a full directory. The -e function lets you give an extension
to which it prints all the files in a directory with that extension.
