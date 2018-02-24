## Circular Linked List Traversal

To traverse a regular linked list, we would start at the head node and stop when next is equal to null.

For a circular linked list, we start at the first node and stop when the same node is reached again.  

### Pseudo Code

```
def traverse_circular_list(first_node):
    temp = first_node
    if first_node != null:
        while temp != first_node:
            print(temp.data())
            temp = temp.next()

```
