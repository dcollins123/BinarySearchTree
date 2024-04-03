# BinarySearchTree
CS 300 Module Five Assignment Guidelines and Rubric
Overview
GitHub

eBid_Monthly_Sales.csv (larger set of 12,023 bids)
eBid_Monthly_Sales_Dec_2016.csv (smaller set of 76 bids)
This assignment is designed to explore linked lists, so you will implement a singly linked list to hold a collection of bids loaded from a CSV file. We provide a starter console program that uses a menu to enable testing of the hash table logic you will complete. It also allows you to pass in the path to the bids CSV file to be loaded, enabling you to try both files. In this version, the following menu is presented when the program is run:

Menu:

Load Bids
Display All Bids
Find Bid
Remove Bid
Exit
Enter choice:

The BinarySearchTree.cpp program is partially completed. It contains empty methods representing the programming interface used to interact with a binary search tree. You will need to add logic to the methods to implement the necessary behavior. Here is the public API for BinarySearchTree.cpp that you have to complete:

public:

BinarySearchTree();
virtual ~BinarySearchTree();
void Insert(Bid bid);
void Remove(string bidId);
Bid Search(string bidId);

Prompt
You will need to perform the following steps to complete this activity:

Setup: Begin by creating a new C++ project with a project type of "Hello World C++ Project".

Name the project “BinarySearchTree”. Remember to pick the correct compiler in Toolchains and click Finish. This will create a simple BinarySearchTree.cpp source file under the /src directory.
Download the starter program files and copy them to the project’s /src directory, replacing the existing auto-generated ones. Remember to right-click on the project in the Project Explorer pane on the left and Refresh the project so it adds all the new files to the src folder underneath.
Because this activity uses C++ 11 features, you may need to add the -std=c++11 compiler switch to the miscellaneous settings.
Task 1: Define structures for tree node and housekeeping variables.

Task 2: Implement inserting a bid into the tree.

Task 3: Implement removing a bid from the tree.

Task 4:Implement searching the tree for a bid.

Task 5: Complete the function to display all bids. Note that you may be able to reuse a portion of your code from a previous assignment to save you time. Look for where you have used a Node structure to implement a linked list.

Here is sample output from running the completed program:

> ./BinarySearchTree ~/Downloads/eBid_Monthly_Sales.csv
> BinarySearchTree.exe Downloads\eBid_Monthly_Sales.csv

Load bids from CSV and display the hash table contents:

Example Input	Choice: 1	Choice: 43
Display	Menu:
1. Load Bids
2. Display All Bids
3. Find Bid
4. Remove Bid
9. Exit
Enter choice: 1	Menu:
1. Load Bids
2. Display All Bids
3. Find Bid
4. Remove Bid
9. Exit
Enter choice: 3
Output	
Loading CSV file eBid_Monthly_Sales.csv
12,023 bids read
time: 6795773 clock ticks
time: 6.79577 seconds

98129: Printer | 52.00 | Enterprise
time: 183 clock ticks
time: 0.000183 seconds
Note that it took only 183 clock ticks to search over 12,000 records in a binary tree.

Your submission must address the following rubric criteria:

Code Reflection: A brief explanation of the code and its purpose, and a brief discussion of your experience in developing it, including any issues that you encountered while completing the exercise and what approaches you took to solve them
Pseudocode or Flowchart: A pseudocode or flowchart description of the code that is clear and understandable and captures accurate logic to translate to the programming language
Specifications and Correctness: Source code must meet its specifications and behave as desired. Correct code produces the correct output as defined by the data and problem; however, you should also produce fully functioning code (with no errors) that aligns with as many of the specifications as possible. You should write your code in such a way that the submitted file executes, even if it does not produce the correct output. You will be given credit for partially correct output that can be viewed and seen to be partially correct.
Annotation / Documentation: All code should also be well-commented. This is a practiced art that requires striking a balance between commenting everything, which adds a great deal of unneeded noise to the code, and commenting nothing. Well-annotated code requires you to:
Explain the purpose of lines or sections of your code, detailing the approach and method you took to achieve a specific task in the code.
Document any section of code that is producing errors or incorrect results.
Modular and Reusable: Programmers should develop code that is modular and reusable. If it contains functionality and responsibility in distinct methods, code is more flexible and maintainable. Your code should adhere to the single responsibility principle—classes and methods should do only one job. If you can replace a method with another that uses a different technique or implementation without impacting (having to refactor or rewrite) other parts of your code, then you have succeeded in creating modular methods.
Readability: Code needs to be readable to a knowledgeable programmer. In this course, readable code requires:
Consistent, appropriate whitespace (blank lines, spaces) and indentation to separate distinct parts of the code and operations
Explicit, consistent variable names, which should clearly indicate the data they hold and be formatted consistently: for example, numOrders (camelCase) or item_cost (underscored)
Organized structure and clear design that separates components with different responsibilities or grouping-related code into blocks
What to Submit
To complete this assignment, submit the CPP code files and a code reflection and associated pseudocode or flowchart. Your written portion should be 1–2 paragraphs in length. Submit the written portion by typing in the Text Submission box, and submit the code as a separate file attachment.

Supporting Materials
CS 300 Binary Search Tree Assignment Student Files.zip
Download this zipped file folder to begin your assignment. The data sets you will use in this assignment are provided in these comma-separated files:

eBid_Monthly_Sales.csv (larger set of 12,023 bids)
eBid_Monthly_Sales_Dec_2016.csv (smaller set of 76 bids)
BinarySearchTree.cpp program, which is a partially completed program that you can use as a starting point for the assignment
