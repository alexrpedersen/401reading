# Linked Lists

## What is a Linked List

#### A linked list is a sequence of Nodes that are connected/linked to each other. Each Node references the next Node in the link, but when it comes to linked list there are two types of linked lists - Singly and Doubly. 

## Terminology

- Linked List
#### A data structure that contains nodes that links/points to the next node in the list.
- Singly
#### Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
- Doubly
#### Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
- Node
#### Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
- Next
#### Each node contains a property called Next. This property contains the reference to the next node.
- Head
#### The Head is a reference type of type Node to the first node in a linked list.
- Current
####  The Current reference is a reference type of type Node that is currently being looked at. This node is traditionally used when traversing through a full linked list. When traversing, you typically reset the current to the head to guarantee you are starting from the beginning of the linked list.

## Travering Linked Lists

#### When travering linked lists you are not able to use foreach or for loops. We use Next. The best way to approach a traversal is through the use of a while() loop. The allows us to continually check that the Next node in the list is not null. 

#### Once we are in the while loop, we are checking if the value of the current node is equal to the value we are looking for. Given the logic, if that condition is true, then we have found the value we were looking for, so we return true.

#### If the Current node does not contain the value we are looking for, we then must move Current to the next node that is being referenced. Again, because the condition of this while loop is to only run if we are still at a node, we can safely traverse to the next node without fear of getting a NullReferenceException.

## Attached Is a quick reference
- https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html
- 