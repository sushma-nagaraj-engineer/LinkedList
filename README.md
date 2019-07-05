# LinkedList
In this project I have added the following methods to perform various operations on a LinkedList,

 1) Swap
 Receives two index positions as parameters, and swaps the nodes at
 these positions by changing the links, provided both positions are 
 within the current size
 2) Shift
 Receives an integer (positive or negative) and shifts the list this
 many positions forward (if positive) or backward (if negative).  
    1,2,3,4    shifted +2    3,4,1,2
    1,2,3,4    shifted -1    4,1,2,3
 3) Erase 
 Receives an index position and number of elements as parameters, and
 removes elements beginning at the index position for the number of 
 elements specified, provided the index position is within the size
 and together with the number of elements does not exceed the size
 4) InsertList
 receives another MyLinkedList and an index position as parameters, and 
 copies the list from the passed list into the list at the specified
 position, provided the index position does not exceed the size.
 Main
 add code to the main method to demonstrate each of your methods
