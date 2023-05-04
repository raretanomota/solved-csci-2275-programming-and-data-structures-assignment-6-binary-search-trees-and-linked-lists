Download Link: https://assignmentchef.com/product/solved-csci-2275-programming-and-data-structures-assignment-6-binary-search-trees-and-linked-lists
<br>
An online movie service needs help keeping track of their stock. You should help them by developing a program that stores the movies in a Binary Search Tree (BST) ordered by the first letter in the movie title, and then a singly linked list for each node in the BST that includes the information for the movie. For each of the movies in the store’s inventory, the following information is kept:

– IMDB ranking – Title

– Year released

– Quantity in stock

Your program will have a menu similar to previous assignments from which the user could select options. In this assignment, your menu needs to include options for finding a movie, renting a movie, printing the inventory, deleting a movie, and quitting the program.

Your program needs to incorporate the following functionality. These are <strong>not </strong>menu options, see Appendix A for the specific menu options.

<strong>Insert all the movies into the tree</strong>.

When the user starts the program they will pass it the name of the text file that contains all movie information. Each line in the file shows the IMDB ranking, title, year released, and quantity in stock. Your program needs to handle that command line argument, open the file, and read all movie data in the file.

From this data, build the BST ordered by the first letter in the movie title. For each of the nodes in the BST, there should b e a sorted singly linked list of the actual movie data. <em>Note: the nodes should be added to the BST and Linked Lists </em><em>in the order they are read in. </em>The name of the file that contains the movie data is Assignment6Movies.txt.

<strong>Find a movie.</strong>

When the user selects this option from the menu, they should be prompted for the name of the movie. Your program should then search the tree and singly linked lists and display all information for that movie. If the movie is not found, your program should display, “Movie not found.”