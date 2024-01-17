# Linked-Lists
This repository consists of Linked Lists Problems







/*

What is LinkedLists?

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations.

In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.

Linked List is a linear data structure, in which elements are not stored at a contiguous location, rather they are linked using pointers.
Linked List forms a series of connected nodes, where each node stores the data and the address of the next node.



Why linked list data structure needed?
Here are a few advantages of a linked list that is listed below, it will help you understand why it is necessary to know.



Dynamic Data structure: The size of memory can be allocated or de-allocated at run time based on the operation insertion or deletion.

Ease of Insertion/Deletion: The insertion and deletion of elements are simpler than arrays since no elements need to be shifted after insertion and deletion, Just the address needed to be updated.

Efficient Memory Utilization: As we know Linked List is a dynamic data structure the size increases or decreases as per the requirement so this avoids the wastage of memory.

Implementation: Various advanced data structures can be implemented using a linked list like a stack, queue, graph, hash maps, etc.


Example:

In a system, if we maintain a sorted list of IDs in an array id[] = [1000, 1010, 1050, 2000, 2040].

If we want to insert a new ID 1005, then to maintain the sorted order, we have to move all the elements after 1000 (excluding 1000).

Deletion is also expensive with arrays until unless some special techniques are used. For example, to delete 1010 in id[],
everything after 1010 has to be moved due to this so much work is being done which affects the efficiency of the code.




Advantages of Linked Lists            ||          Disadvantages
                                      ||
        Dynamic Size                  ||            Random Access
        Insertion and Deletion        ||            Extra Memory
        Searching                     ||


//How LinkedList looks?

HEAD
data,next  ------>  data,next --------> data,next --------> NULL
NODE                 NODE                 NODE



This is all you should know, In case you didnt understand this it is completly Okay , ignore this and focus on the basic problems first
then slowly things will catch up.....



![image](https://github.com/ramanaguru/Linked-Lists/assets/121872409/7194c111-603e-4ac7-8477-f66723b694e2)

*/
