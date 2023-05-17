# class 08

Teaching: Using an analogy to explain linked lists

Let's imagine you have a grocery list, and you want to keep track of the items you need to buy. You decide to use a piece of paper and write down the items one below the other. Each item on the list represents a node, and the connection between them is like a linked list.

An analogy can help us understand how linked lists work. In this analogy, each item on the grocery list is a node, and the connection between them is like a pointer. Let's go through the steps:

You start with an empty grocery list, which is like an empty linked list.

You write down the first item you need to buy, let's say "Apples." This is like adding a node to the linked list.

Then, you write down the next item, "Bananas," below "Apples." You draw an arrow from "Apples" to "Bananas," representing the connection between the nodes.

You continue adding items to the list and drawing arrows to connect them, just like adding nodes and linking them in a linked list.

Now, imagine you want to find the second-to-last item on the list. You start at the beginning of the list and follow the arrows until you reach the second-to-last item.

Finally, you can read the value of that item, which represents the second-to-last node's value in the linked list.

This analogy helps to visualize the concept of linked lists, where each node contains a value and a reference to the next node. The connection between nodes allows traversal through the list to access specific nodes.

Stacks and Queues are data structures that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

Common terminology for a stack is Push, Pop, Top, Peek, and IsEmpty.

Stacks follow these concepts: FILO First In Last Out, LIFO Last In First Out, and Stack Visualization.

When pushing something to the stack, it becomes the new top, and when popping something from the stack, it pops the current top and sets the next top as top. Pushing a Node onto a stack will always be an O(1) operation.

The most important details in this text are the steps involved in adding a Node to a stack.

When adding a Node, it is assigned as the new top, with its next property equal to the original top.

When adding a Node, it is re-assigned to the Node that lives below and the top Node is returned to the user.

Popping a Node off a stack is the action of removing a Node from the top.

Typically, you would check isEmpty before conducting a pop to ensure that an exception is not raised.

A Queue is a list of Nodes or items that are added or removed from the queue.

Peek is the action of viewing the value of the front Node in the queue.

If called when the queue is empty, an exception will be raised.

Peek O(1)

ALGORITHM peek()
// INPUT <-- none
// OUTPUT <-- value of the front Node in Queue
// EXCEPTION if Queue is empty

   return front.value