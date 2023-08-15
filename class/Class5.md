**Big O Notation:**
- Big O notation explains how fast an algorithm works and how much memory it needs.
- It considers Running Time (time to finish) and Memory Space (memory used).
- We focus on worst-case scenarios.
- Four main aspects: Input Size, Units of Measurement, Orders of Growth, Best/Worst/Average Cases.
- We use 'n' to represent input size, bigger 'n' may mean more time/memory.
- Notations like Big O, Big Omega, and Big Theta describe an algorithm's behavior.
- Summary: Big O helps us know how fast an algorithm works and its memory usage based on input size, focusing on worst-case.

**Linked List:**
- A Linked List is like a chain of connected boxes (Nodes).
- Nodes hold data and point to the next box.
- Types: Singly Linked Lists (one arrow) and Doubly Linked Lists (arrows both ways).
- Moving through the list means following the arrows from box to box.
- To find something, we follow the arrows and check boxes until we find it.
- Adding a new box:
  - Beginning: Create a box, link it to the first one, and make it the new first.
  - Middle: Find the right spot and rearrange arrows.
- Printing shows the data in each box one by one.
- Big O tells us how fast these actions are as the list gets bigger:
  - Going through: Slower with a bigger list (O(n)).
  - Adding a box: Fast at the start, slower in the middle (O(1) or O(n)).
  - Printing: Slower with a bigger list (O(n)).
- Linked List is like connected boxes, and Big O helps us understand their speed.
