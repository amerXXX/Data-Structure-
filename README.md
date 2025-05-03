# Data-Structure-
A Java-based personal dictionary application implemented using an AVL tree for efficient storage and retrieval of words.

# Features

Add, find, and remove words

Search for similar words (by single-character edit distance)

Save and load dictionary from a file

# Project Structure

dictionary/
├── AVLTree.java      # Self-balancing binary search tree
├── BST.java          # Binary search tree base class
├── BinaryTree.java   # General tree utilities
├── BTNode.java       # Tree node definition
├── Dictionary.java   # Main dictionary logic and CLI
├── SLL.java          # Singly linked list for helper lists
└── mydictionary.txt  # Sample word list

# Getting Started

# Prerequisites

Java 8 or higher

Maven or your preferred build tool (optional)

# Installation

Clone the repository:

git clone https://github.com/<your-username>/dictionary-avl.git
cd dictionary-avl

(Optional) Build with Maven:

mvn compile

Running the Application

javac dictionary/*.java
java dictionary.Dictionary

You can then use commands like load, find, add, remove, similar, save, and exit at the prompt.

.gitignore

# Compiled Java classes
*.class

# Eclipse/IntelliJ project files
*.classpath
*.project
*.idea/
*.iml

# Build directories
target/

License

MIT License © 2025 Amer Aziz Almutairi
