# Stack Implementation in Java (Linked List Based)

This project demonstrates a **Stack data structure** implemented using a **linked list** in Java. The stack supports basic operations such as:

- **Push** (Add an element to the top)
- **Pop** (Remove and return the top element)
- **Peek** (View the top element without removing it)
- **Reverse** (Reverse the stack order)
- **Insert at Bottom** (Insert an element at the bottom of the stack)
- **Display** (Print all elements in the stack)

## 🚀 Features
- Implemented using **singly linked list**.
- No fixed size limit (dynamic memory allocation).
- **Efficient in-place reversal**.
- Additional functionality to **insert at the bottom**.
- Fully documented with comments.

## 📜 Code Overview
The `Stack` class uses a **linked list-based approach** where each node has:
- `data`: Stores the integer value.
- `next`: Points to the next node in the stack.

The `Node` class represents each element in the stack.

## 🛠 Methods
### 1️⃣ **isEmpty()**
- Checks if the stack is empty.

### 2️⃣ **push(int data)**
- Adds a new element to the top of the stack.

### 3️⃣ **pop()**
- Removes and returns the top element.
- If the stack is empty, it prints `"Stack is empty!"`.

### 4️⃣ **peek()**
- Returns the top element without removing it.
- If the stack is empty, it prints `"Stack is empty!"`.

### 5️⃣ **reverse()**
- Reverses the stack using an **extra stack**.

### 6️⃣ **insertAtBottom(int data)**
- Inserts an element at the bottom of the stack.

### 7️⃣ **display()**
- Prints all stack elements in order.

## 📌 Example Usage
```java
Stack s = new Stack();

s.push(1);
s.push(2);
s.push(3);
s.push(4);

System.out.println("Original Stack:");
s.display();

s.reverse();
System.out.println("Reversed Stack:");
s.display();

s.insertAtBottom(5);
System.out.println("After Inserting 5 at the Bottom:");
s.display();

