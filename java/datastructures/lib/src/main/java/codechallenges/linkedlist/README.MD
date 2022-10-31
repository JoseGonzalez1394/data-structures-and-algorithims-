# Singly Linked List
Node:

- Create a Node class that has properties for the value stored in the Node, and a pointer to the next Node.

Linked List:
- Create a Linked List class
- Within your Linked List class, include a head property.
  - Upon instantiation, an empty Linked List should be created.
- The class should contain the following methods
  - insert
    - Arguments: value
    - Returns: nothing
    - Adds a new node with that value to the head of the list with an O(1) Time performance.
  - includes
    - Arguments: value
    - Returns: Boolean
      - Indicates whether that value exists as a Node’s value somewhere within the list.
  - to string
    - Arguments: none
    - Returns: a string representing all the values in the Linked List, formatted as:
    "{ a } -> { b } -> { c } -> NULL"
## Challenge
Test for Functionality:
- Can successfully instantiate an empty linked list
- Can properly insert into the linked list
- The head property will properly point to the first node in the linked list
- Can properly insert multiple nodes into the linked list
- Will return true when finding a value within the linked list that exists
- Will return false when searching for a value in the linked list that does not exist
- Can properly return a collection of all the values that exist in the linked list

## Approach & Efficiency
Inserting into the list is O(1) because we can add it directly without any traversal. Traversing the list is O(N) in the worst case of traversing the entire list.
## API
public void insert(int value) The insert method takes an integer as an argument and adds this integer to the beginning of the linked list.

public boolean includes(int value) The includes method takes and integer as an argument and returns true if the integer value is found in the list.

public String toString() The toString method overides the default toString method and return a string representation of the elements in the linked list.
## Resources
https://www.javatpoint.com/java-linkedlist
https://www.youtube.com/watch?v=YQQio9BGWgs
https://github.com/akkanben/data-structures-and-algorithms/blob/main/java/datastructures/singly-linked-list-readme.md
