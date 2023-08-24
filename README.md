# Binary Search Tree

```
Binary Search Tree is a node-based binary tree data structure which has the following properties:

- The left subtree of a node contains only nodes with keys lesser than the node’s key.
- The right subtree of a node contains only nodes with keys greater than the node’s key.
- The left and right subtree each must also be a binary search tree.
```

# Binary Search Tree Visualization

This project visualizes a binary search tree using OpenGL in C++.

## Features

* Construct a binary search tree from user input
* Visualize the tree structure
* Implement core BST operations like insertion, deletion, etc.

## Usage

1. Clone the repository
2. Install OpenGL and C++ compiler
3. Compile the project using GCC
4. Run the executable

## Installation

### On Linux

1. Install OpenGL:
```bash
    sudo apt install libglu1-mesa-dev freeglut3-dev mesa-common-dev
```

2. Clone the repository: 
```bash
    git clone https://github.com/reddy0852/binarysearchtreecgv.git
```
3. Compile the project: `gcc *.c -lGL -lGLU -lglut`

4. Run the executable: `./binary_search_tree`

    - The application window will open.
    - Enter input integers when prompted and ask user to enter the number to construct nodes for the binary tree. 
    - The binary search tree will be constructed and displayed in the OpenGL window.



## Structure
The project consists of the following files:
- `BST.cpp` - Contains Binary Search Tree implementation.
- `Node.cpp` - Defines the Node structure for the tree.
- `button.cpp` - Handles button interaction (if applicable).
- `global.cpp` - Contains global variables and functions.
- `main.cpp` - Main application logic.
- `modal.cpp` - Handles modal dialogs 

