## Analogy: Built-In Packages are like Toolkits

Imagine you're a carpenter and you have a toolbox filled with tools you often use. These tools are organized into different sections for various tasks, making it easier for you to find what you need. In Java, built-in packages are like these organized toolkits. They contain ready-made tools (classes and interfaces) for specific tasks that programmers commonly do.

### Examples of Built-In Packages:

java.io
java.lang
java.util

## Creating a New Package in IntelliJ:

* Find the Right Spot: Imagine you have a toolbox for carpentry. Before you start working on a specific project, you might grab tools that belong to that project.

* Create a New Toolbag: In IntelliJ, you right-click in the project area where you want your new tools to be kept. You select "New" and then "Package." It's like creating a new bag for your tools.

* Name Your Bag: You give the bag a name, but in the Java world, we call it a package. For example, if you're building furniture, you might create a package named "furniture.tools."

* Store Your Tools: Now, you put your specific tools (Java classes and stuff) into this bag (package) you just created.

* Use Your Tools: Whenever you're working on furniture, you know exactly where your furniture-related tools are. Similarly, in IntelliJ, when you're working on code related to furniture, you know where to find your "furniture.tools" package.




## Which loop types use a loop counter?

The loop types that use a loop counter are the "For Loop" .

## Difference between While and Do-While loops?

the key difference is that the "While Loop" checks the condition before executing the loop body, which means the loop might not run at all. On the other hand, the "Do-While Loop" executes the loop body first and then checks the condition, ensuring the loop body runs at least once.

## 3 Built-In Methods for Arrays


* binarySearch(Object[] a, Object key): This method helps find something in an ordered list (array) really fast. It's like when you look for a word in a dictionary by quickly opening it in the middle and deciding if you need to go left or right. If it finds the thing you're looking for, it tells you where; otherwise, it suggests where you should put it to keep the list in order.

* equals(long[] a, long[] a2): This method compares two lists (arrays) to see if they're exactly the same. It checks if they have the same number of things and if each thing in one list matches the corresponding thing in the other. It's like checking if two shelves of toys have the exact same toys in the same order.

* fill(int[] a, int val): This method quickly puts the same thing into all the boxes of a shelf (array). Imagine you have a shelf for toys, and you want to put the same toy in every box. This method helps you do it easily. And yes, there are similar methods for different types of things you might want to put in those boxes.



## How is the size of an array determined in Java?

In Java, the size of an array is determined when the array is created. Once the size is set, it cannot be changed. When you create an array, you need to specify its size, which is the number of elements it can hold.