# Linked-List-VISUALIZER

A simple, interactive tool built with **HTML**, **CSS**, and **JavaScript** to visualize and interact with different types of linked lists, including singly linked lists, doubly linked lists, and circular linked lists. This project helps you understand the structure and operations of linked lists in an intuitive way.

---

## Features

* **Interactive Linked Lists**: Easily create, modify, and visualize linked lists.
* **Graphical Representation**: Real-time graphical updates as you perform operations like insertion, deletion, and reversal.
* **Support for Various Linked List Types**:

  * Singly Linked List
  * Doubly Linked List
  * Circular Linked List
* **Real-Time Visualization**: Operations such as adding, removing, and modifying nodes are visually represented.
* **Step-by-Step Updates**: Watch the list update as you perform various operations to better understand how linked lists work.

---

## Demo

Check out the live demo of the **Linked-List-VISUALIZER** here: https://ankitkumar-dev25.github.io/Linked-List-VISUALIZER/

---

## Installation

To run the **Linked-List-VISUALIZER** on your local machine, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone (https://github.com/ANKITKUMAR-dev25/Linked-List-VISUALIZER.git)
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Linked-List-VISUALIZER
   ```

3. **Open the index.html file** in your web browser.

   You can simply double-click on `index.html` to view the application in your browser.

---

## Usage

1. **Select Linked List Type**: Choose between singly, doubly, or circular linked lists using the options provided in the UI.
2. **Add Nodes**: Add new nodes to the list by selecting the position (head, tail, or a specific index).
3. **Delete Nodes**: Remove nodes from the list either by specifying a position or choosing the head/tail.
4. **Reversal**: Reverse the linked list and visualize the change in order.
5. **Visualization**: The list structure is drawn dynamically using JavaScript and updated as you interact with the tool.

---

## File Structure

```
/Linked-List-VISUALIZER
|-- index.html         # Main HTML file for the visualizer
|-- style.css          # Styles for the visual representation of the list
|-- script.js          # JavaScript for linked list logic and interactivity
|-- assets/            # Optional: images or additional assets
|-- README.md          # Project documentation (this file)
```

---

## Technologies Used

* **HTML**: The structure of the webpage and the user interface.
* **CSS**: For styling the visualization, list nodes, and interactive elements.
* **JavaScript**: For implementing the linked list data structure and controlling the interactions (insertion, deletion, traversal, reversal).

  * Basic DOM manipulation for the dynamic updates of the list.

---

## How It Works

### 1. **Linked List Operations**

The tool supports the following operations on linked lists:

* **Insertion**:

  * Insert at the beginning
  * Insert at the end
  * Insert at a specific position

* **Deletion**:

  * Delete from the beginning
  * Delete from the end
  * Delete from a specific position

* **Traversal**: Traverse and print the elements of the list in the console.

* **Reversal**: Reverse the order of nodes in the linked list.

### 2. **Visualization**

* The linked list is represented as a series of connected nodes, with each node drawn as a box.
* **Singly Linked List**: Each node has a pointer to the next node.
* **Doubly Linked List**: Each node has pointers to both the next and previous nodes.
* **Circular Linked List**: The last node's pointer points back to the first node.

### 3. **CSS Styling**

The nodes are styled using **CSS** to represent the structure of the linked list visually. The lines connecting nodes and the nodes themselves change dynamically when an operation is performed.

### 4. **JavaScript Logic**

* JavaScript controls the linked list logic (insert, delete, reverse, etc.) by manipulating the DOM elements representing the nodes.
* It dynamically adds or removes `div` elements and updates the connections between them.

---

## Example Usage

1. **Add Nodes**:
   Click the "Add Node" button to add a new node at the beginning, end, or a specific index of the list.

2. **Delete Nodes**:
   Click the "Delete Node" button to remove nodes from the list at any position.

3. **Reversal**:
   Click the "Reverse List" button to reverse the entire list.

---

## Contributing

We welcome contributions! If you'd like to improve the project or fix bugs, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Open a pull request.



