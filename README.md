PROJECT TITLE:- Gate-Allocation-Tree-CRUD

Team Members:-

N Lakshmi Vijayanand Reddy
V Kiran Rathore
Problem Statement:-

In many real-world applications, data needs to be dynamically added, updated, deleted, and displayed efficiently.
This project aims to implement a dynamic data management system using a Linked List in C to perform CRUD operations.

Data Structure Used:- This project uses a Singly Linked List.

Each node stores:
Data (integer)
Pointer to next node
Dynamic memory allocation is used (malloc, free)
Algorithm Explanation:- Create (Add Node):-

Create a new node using malloc
Insert it at the end of the list
Read (Display):-

Traverse the list from head
Print each node value
Update:-

Search for a node with given value
Replace it with new value
Delete:-

Find the node
Adjust links of previous node
Free memory using free()
Search:-

Traverse list
Compare each node value
Return position if found
Compilation Instructions:-

Step 1: Open terminal in project folder

Step 2: Compile the program

gcc main.c -o program

Step 3: Run the program

./a.exe

Sample Output:-

--- MENU ---

1.Add Node

2.Delete Node

3.Update Node

4.Search

5.Display

6.Exit

Example:-

1.Enter your choice: 1

Enter data: 10

Node added successfully!
2.Enter your choice: 1

Enter data: 20

Node added successfully!
3.Enter your choice: 5

Linked List: 10 -> 20 -> NULL
sample output screenshots:-
<img width="895" height="520" alt="image" src="https://github.com/user-attachments/assets/54f3fa4c-a1c5-4ddc-8c93-aadd13e56c26" />
<img width="1100" height="572" alt="image" src="https://github.com/user-attachments/assets/c969e2dd-5d75-446f-9089-33cfb370b046" />
<img width="1125" height="592" alt="image" src="https://github.com/user-attachments/assets/2d7d3dd6-ddb2-4d1c-b063-9262d0c2ea3f" />
<img width="1174" height="662" alt="image" src="https://github.com/user-attachments/assets/4bf5eedc-9e1d-4736-beac-3645bee10b56" />
Demo Video:
https://drive.google.com/file/d/10DuJWj7gXLBCmczpTQ9QrAAzZ8EMLBJr/view?usp=drive_link



