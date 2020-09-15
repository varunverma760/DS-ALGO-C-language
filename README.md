# DS-ALGO-C-language

Expeiment 1 :- Linear Search : -








Linear search in C to find whether a number is present in an array. If it's present, then at what location it occurs. It is also known as a sequential search. It is straightforward and works as follows: we compare each element with the element to search until we find it or the list ends. Linear search for multiple occurrences and using a function.



The time complexity of above algorithm is O(n).

Linear search is rarely used practically because other search algorithms such as the binary search algorithm and hash tables allow significantly faster searching comparison to Linear search.




Experiment 2:-









Experiment 3:- write a program to implement singly linked list









Linked List
Linked List can be defined as collection of objects called nodes that are randomly stored in the memory.
A node contains two fields i.e. data stored at that particular address and the pointer which contains the address of the next node in the memory.
The last node of the list contains pointer to the null.
DS Linked List



![image](https://miro.medium.com/max/1200/1*Z3vqMccS0Y8q7LVgvlyQ9A.png)






![image](https://static.javatpoint.com/ds/images/linked-list.png)




![image](https://media.geeksforgeeks.org/wp-content/uploads/20200318172830/ezgif.com-gif-maker2.gif)








Uses of Linked List:-





The list is not required to be contiguously present in the memory. The node can reside any where in the memory and linked together to make a list. This achieves optimized utilization of space.
list size is limited to the memory size and doesn't need to be declared in advance.
Empty node can not be present in the linked list.
We can store values of primitive types or objects in the singly linked list.




Why use linked list over array?





Till now, we were using array data structure to organize the group of elements that are to be stored individually in the memory. However, Array has several advantages and disadvantages which must be known in order to decide the data structure which will be used throughout the program.

Array contains following limitations:

The size of array must be known in advance before using it in the program.
Increasing size of the array is a time taking process. It is almost impossible to expand the size of the array at run time.
All the elements in the array need to be contiguously stored in the memory. Inserting any element in the array needs shifting of all its predecessors.
Linked list is the data structure which can overcome all the limitations of an array. Using linked list is useful because,


It allocates the memory dynamically. All the nodes of linked list are non-contiguously stored in the memory and linked together with the help of pointers.
Sizing is no longer a problem since we do not need to define its size at the time of declaration. List grows as per the program's demand and limited to the available memory space.







![image](https://secureservercdn.net/160.153.138.219/b79.d22.myftpupload.com/wp-content/uploads/2015/09/Singly-linked-list.png)






Operations in Singly linked list


Insertion :-



The insertion into a singly linked list can be performed at different positions. Based on the position of the new node being inserted, the insertion is categorized into the following categories.


1. Insertion at the beginning : -



It involves inserting any element at the front of the list. We just need to a few link adjustments to make the new node as the head of the list.





![image](https://secureservercdn.net/160.153.138.219/b79.d22.myftpupload.com/wp-content/uploads/2015/09/insertion-of-node-at-beginning-of-singly-linked-list2.png)



2. Insertion at the end of the list :-


It involves insertion at the last of the linked list. The new node can be inserted as the only node in the list or it can be inserted as the last one. Different logics are implemented in each scenario.








![image](https://secureservercdn.net/160.153.138.219/b79.d22.myftpupload.com/wp-content/uploads/2015/09/insertion-of-node-at-end-of-singly-linked-list2.png)





3. Insertion at the specific node : -



It involves insertion after the specified node of the linked list. We need to skip the desired number of nodes in order to reach the node after which the new node will be inserted. .



![image](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/types-of-linked-list-and-operation-on-linked-list-insert-after-5628be6cb96413e0.png)






Deletion
















Experiment 4 :- write a program to implement doubly linked list










Experiment 5:- write a program to implement circular linked list









Experiment 6 :- write implement stack as an array and linked list
