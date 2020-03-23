Answer the following questions for each of the data structures you implemented as part of this project.

## Queue

1. What is the runtime complexity of `enqueue`?
O(1). There's no need to iterate over each item to add one item.

2. What is the runtime complexity of `dequeue`?
O(1). There's no need to iterate over each item to remove one item.

3. What is the runtime complexity of `len`?
O(1). Size is updated as items are added / removed.

## Binary Search Tree

1. What is the runtime complexity of `insert`? 
O(log n). Each comparison halves the number of possible positions still to consider.

2. What is the runtime complexity of `contains`?
O(log n). Each comparison halves the number of possible values still to consider.

3. What is the runtime complexity of `get_max`? 
O(1). There is only one way to get to max - traverse the RHS of the tree.

## Heap

1. What is the runtime complexity of `_bubble_up`?

2. What is the runtime complexity of `_sift_down`?

3. What is the runtime complexity of `insert`?

4. What is the runtime complexity of `delete`?

5. What is the runtime complexity of `get_max`?

## Doubly Linked List

1. What is the runtime complexity of `ListNode.insert_after`?
O(1). It's given the node to insert after.

2. What is the runtime complexity of `ListNode.insert_before`?
Same as above.

3. What is the runtime complexity of `ListNode.delete`?
O(1). You give it the node to delete.

4. What is the runtime complexity of `DoublyLinkedList.add_to_head`?
O(1). There's no need to iterate over each item to add one item.

5. What is the runtime complexity of `DoublyLinkedList.remove_from_head`?
O(1). There's no need to iterate over each item to remove one item.

6. What is the runtime complexity of `DoublyLinkedList.add_to_tail`?
O(1). There's no need to iterate over each item to add one item.

7. What is the runtime complexity of `DoublyLinkedList.remove_from_tail`?
O(1). There's no need to iterate over each item to remove one item.

8. What is the runtime complexity of `DoublyLinkedList.move_to_front`?
O(1). You're given the node to move to front, so you just have to update pointers.

9. What is the runtime complexity of `DoublyLinkedList.move_to_end`?
O(1). You're given the node to move to end, so you just have to update pointers.

10. What is the runtime complexity of `DoublyLinkedList.delete`?
O(1). You're given the node to delete, so you just have to update pointers.

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the JS `Array.splice` method. Which method generally performs better?
    DLL delete. Array.splice() requires iteration over the items from start to end.