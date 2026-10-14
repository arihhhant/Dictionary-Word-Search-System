Dictionary / Word Search System Using Binary Search Tree (BST) in C

1. Introduction

The Dictionary / Word Search System is a console-based application developed using the C programming language. It allows users to store words along with their meanings, search for any stored word, and display all words in alphabetical order. The project uses the Binary Search Tree (BST) data structure, which provides efficient insertion and searching operations. This project demonstrates the practical application of data structures in building a simple digital dictionary.

2. Objectives

- To implement a dictionary using Binary Search Tree (BST).
- To store words and their meanings efficiently.
- To search words quickly using BST.
- To display all words in alphabetical order.
- To understand the implementation and traversal of Binary Search Trees.

3. Problem Statement

Searching for words manually in a large dictionary is time-consuming. A computerized dictionary can perform searches much faster by storing words in a Binary Search Tree. This project provides a simple solution for adding, searching, and displaying words using BST.

4. Features

- Add a new word with its meaning.
- Search any word from the dictionary.
- Display all words in alphabetical order.
- Menu-driven interface.
- Efficient searching using Binary Search Tree.

5. Software Requirements

- Operating System: Windows or Linux
- Programming Language: C
- Compiler: GCC, Turbo C, CodeBlocks, or VS Code
- Memory Requirement: 512 MB RAM or above

6. Data Structure Used

Binary Search Tree (BST)

A Binary Search Tree is a hierarchical data structure in which:

- The left child contains words smaller than the parent.
- The right child contains words greater than the parent.
- Searching and insertion are performed efficiently.

7. Structure Used

struct Node
{
    char w[20];
    char m[100];
    struct Node *l;
    struct Node *r;
};

Description

- w – Stores the word.
- m – Stores the meaning of the word.
- l – Pointer to the left child.
- r – Pointer to the right child.

8. Functions Used

insert() – Inserts a new word and its meaning into the BST.

search() – Searches for a word and returns its meaning if found.

display() – Displays all stored words in alphabetical order using Inorder Traversal.

main() – Controls the menu-driven operations and user interaction.

9. Algorithm

Step 1: Start the program.

Step 2: Display the menu.

Step 3: Read the user's choice.

Step 4: If the choice is Add:

- Enter the word.
- Enter its meaning.
- Insert the word into the Binary Search Tree.

Step 5: If the choice is Search:

- Enter the word to search.
- Search the BST.
- Display the meaning if found; otherwise display "Not Found".

Step 6: If the choice is Display:

- Perform Inorder Traversal.
- Display all words alphabetically.

Step 7: If the choice is Exit:

- Terminate the program.

10. Flowchart

                START
                  |
                  V
           Display Menu
                  |
      -----------------------
      |     |      |       |
     Add  Search Display  Exit
      |     |      |       |
      V     V      V       V
 Insert  Search  Inorder   End
  BST     BST   Traversal
      |
      --------Back to Menu--------

11. Sample Output

1. Add
2. Search
3. Display
4. Exit

Enter Choice: 1

Word: Apple
Meaning: A fruit

Enter Choice: 1

Word: Book
Meaning: Collection of pages

Enter Choice: 2

Search: Apple

Meaning: A fruit

Enter Choice: 3

Apple : A fruit
Book  : Collection of pages

12. Advantages

- Fast searching using BST.
- Words are displayed in alphabetical order.
- Easy to understand and implement.
- Efficient insertion and retrieval of data.
- Demonstrates practical use of Data Structures.

13. Limitations

- Delete operation is not implemented.
- Duplicate words cannot be inserted.
- Search is case-sensitive.
- Data is not stored permanently after the program closes.

14. Future Enhancements

- Add Delete functionality.
- Add Update Meaning option.
- Save data in files for permanent storage.
- Load dictionary automatically at startup.
- Develop a Graphical User Interface (GUI).
- Implement Auto-Suggestion while searching.
- Make searching case-insensitive.
- Support multiple meanings for a single word.

15. Applications

- Digital Dictionary
- Vocabulary Learning Software
- Educational Applications
- Word Search Systems
- English Learning Tools

16. Conclusion

The Dictionary / Word Search System successfully demonstrates the implementation of a Binary Search Tree in C. It provides efficient insertion, searching, and alphabetical display of words. The project is simple, user-friendly, and serves as an excellent example of applying data structures to solve real-world problems. It also strengthens the understanding of Binary Search Trees, recursion, and tree traversal techniques.
