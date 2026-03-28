
# CISC2200 Spring 2026 Lab on Stack 

In this lab assignment, we practice **implementing stack using array list**, **using stack to reverse the order**,
and **working with inheritance**.

## Download starter code

From your terminal (mac or WSL/Ubunto) window, you can use the following command to download it:
```
git clone https://github.com/CISC2200-Spring2024/lab4.git
```

## Requirements:

Please implement the following member functions in the **AList.h**. 

1. There are a few errors or inconsistency between **List.h** and **AList.h** that lead to compilation errors. Read the compilation errors carefully to understand what are the causes, and then fix these inconsistency. (Note: **AList** derives from abstract class **List**, and **AList** is not an abstract class.). 
2. (Extra Credit) Create a file named **Stack.h** which declares and implements a class template **Stack** supporting **pop**, **top**, **push**, **is_empty** functions, it should use **AList** as provided to store the elements.
   The following are what each member function on stack means: 
   - ItemType pop(); //pop and return the top element of the stack
   - ItemType top() const; //return the top element of the stack
   - void push(ItemType v); //push a new element onto the top of the stack
   - bool is_empty() const; //return true if the stack is empty; return false if the stack is not empty
3. In the **SLLList.h** file, add a member function called **reverse_print**. This function shall use a stack (You can use your own Stack or the one provided in C++ STL, see slides for an example) to hold the elements in the list as one traverse the linked list, and
   afterwards, pop elements from the stack one by one to display them. This way, the items in the SLList are displayed in reversed order: the last element is displayed first, and the first element (at the bottom of the stak) is displayed last.
   
## Submission:

This lab is due April 11th, by midnight 11:59pm. Please submit your **List.h**, **AList.h**, **Stack.h**  on BB. 
   
