# Stacks & Queues

<hr>

## Links and Resources

- [Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

<hr>

### Stacks

Terminology:

- Push - adding nodes to the top of the stack
- Pop - taking a node off the top of stack
- Top - node at the top
- Peek - looking at the top value
- isEmpty - returns true if stack is empty
- FILO - First in Last out
- LIFO - Last in First Out
- Analogy - stacking plates. First one to be processed will be the last plate that was put on top.

<hr>

### Stack Methods

    class Stacks:
      def __init__(self, node=None):
          self.top = node

### Push

    def push(self, value):
      node = Node(value)
      node.next = self.top
      self.top = node
      return self

### Big O:

- Time: O(1)

### Pop

    def pop(self):
      if self.top is None:
        return None

      popped = self.top.value
      self.top = self.top.next
      return popped

### Big O:

- Time: O(1)

Peek

    def peek(self):
      if self.top is None:
        return None
      return self.top.value

### Big O:

- Time: O(1)

isEmpty

    def isEmpty(self):
      return self.top == None

### Big O:

- Time: O(1)

## Queues

**Terminology**:

- Enqueue - add to queue
- Dequeue - remove from queue
- Front - first node
- Rear - last node
- Peek - view value of front node
- isEmpty - return true if queue is empty
- FIFO - first in first out
- LILO - last in last out
- Analogy - line at the movie theaters. Who ever is first, will be processed first.

## Queue Methods

    class Queue:
      # this implementation used when a queue does not have a rear property
      def __init__(self, node=None):
          self.front = node

## Enqueue

    # this method is used only when a queue does not have a rear property
    def enqueue(self, value):
      node = Node(value)

      if self.front is None:
        self.front = node
        return self

      current = self.front

      while current.next:
        current = current.next

      current.next = node
      return self

### Big O:

- Time: O(n)

## Peek

    def peek(self):
      if self.front is None:
        return None
      return self.front.value

### Big O:

- Time: O(1)

## isEmpty

    def isEmpty(self):
      return self.front == None

### Big O:

- Time: O(1)