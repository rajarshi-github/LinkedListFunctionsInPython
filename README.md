# LinkedListFunctionsInPython
All linked list functions in Python


The LinkedList is a structure with a "head" which can point to either None or a "node".
Additionally "length" attribute tells the number of nodes in the linked list

So we need TWO class definitions - one for Node and one for LinkedList 


_class Node():
    def __init__(self, data):
        self.data = data
        self.next = None
class SinglyLinkedList():
    
    def __init__(self):
        self.head = None
        self.length = 0
_

We have a error class to handle all error messages 

_class LinkedListError(Exception):
    pass
_

Functions included -
1. string representation of a linked list - 

    **__str__**(self)
    
2. length of a linked list -

    **__len__**(self)
    
3. get the data value at a node position , if not present returns None

    **getNodeValue**(self, nodeposition)
    Default value is 0
   
4. print the linked list in reverse 

    **reverse**(head)
    
   Since this uses recursion - it is a static method
   
5. Returns a sorted linked list 
    **sortedList**(llist)

6. Insert a new node at last of the linked list

    **insertNodeAtLast**(self, data)
    
7. Insert a new node at a given position of the linked list

    **insertNodeAtPosition**(self, data, position)
    
8. Delete a node 

    **deleteNode**(self, position)


Additional functions -

1. Compare two linked lists

    **compare_lists** (list1, list2)
    
2. Merge two linked lists and return a sorted linked list

    **mergeAndsortLinkedLists**(list1, list2)
    
    



