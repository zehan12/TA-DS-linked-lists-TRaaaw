Using the linked list class you created in the previous exercise implement stack and queue:

- Implement Stack using the following methods
  - `add` Adds an element to the stack
  - `remove` Removes an element from the stack
  - `peek` returns the first element from the top of the stack
  - `printAll` print all the elements of the stack from one after another from the top
  - `isEmpty` Returns `true` if the stack is empty

**YOU HAVE TO USE LINKED LIST TO STORE DATA**

```js
class Stack {
  // your code goes here
}

// Test 1

const stack = new Stack();

stack.add(10);
stack.add(12);
stack.add(120);
stack.add(1);
stack.add(4);

console.log(stack.remove()); // => 4
console.log(stack.length); // => 4
console.log(stack.remove()); // => 1
console.log(stack.length); // => 3

console.log(stack.peek()); // 120

console.log(stack.isEmpty()); // false

console.log(stack.remove()); // => 120

console.log(stack.add(100)); // 3

console.log(stack.peek()); // => 100

console.log(stack.remove()); // => 100
console.log(stack.remove()); // => 12
console.log(stack.remove()); // => 10

console.log(stack.isEmpty()); // true
```

- Implement Queue using the following methods
  - `enqueue` Add the element to the queue
  - `dequeue` Removes an element from the queue
  - `peek` returns the first element from the top of the queue
  - `printAll` print all the elements of the queue from one after another from the top
  - `isEmpty` Returns `true` if the queue is empty

**YOU HAVE TO USE LINKED LIST TO STORE DATA**

```js
class Queue {
  // your code goes here
}

// Test 1

const queue = new Queue();

queue.enqueue(10);
queue.enqueue(12);
queue.enqueue(120);
queue.enqueue(1);
queue.enqueue(4);

console.log(queue.dequeue()); // => 10
console.log(queue.length); // => 4
console.log(queue.dequeue()); // => 12
console.log(queue.length); // => 3

console.log(queue.peek()); // 120

console.log(queue.isEmpty()); // false

console.log(queue.dequeue()); // => 120

console.log(queue.peek()); // => 1

console.log(queue.dequeue()); // => 1
console.log(queue.dequeue()); // => 4

console.log(queue.isEmpty()); // true
```
