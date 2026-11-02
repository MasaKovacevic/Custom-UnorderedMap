# Custom-UnorderedMap
Custom implementation of an unordered map in C++ using a hash table and separate chaining.

Features

Insertion and deletion of key-value pairs

Element access using operator[]

Searching for elements using find()

Custom iterator for traversing the map

Size tracking and clearing the map

Implementation

The hash table is implemented using vector<vector<pair<K, V>>>, with separate chaining to handle hash collisions.

The project also includes a custom iterator and test cases demonstrating the implemented operations.

Technologies

C++, STL, Templates, Hash Tables

Project Structure

UnorderedMap.h – Class declaration

UnorderedMap.cpp – Map implementation

Iterator.h – Custom iterator implementation

main.cpp – Testing the implemented functionality
