---
title: Dsa
date: 2025-06-29
author: Your Name
cell_count: 73
score: 70
---

```python
# Stack using List
stack = []

```


```python
# Pushing elements
stack.append(10)
stack.append(20)
stack.append(30)
print("Stack after pushes:", stack)

```

    Stack after pushes: [10, 20, 30]
    


```python

# Popping elements
stack.pop()
print("Stack after pop:", stack)

```

    Stack after pop: [10, 20]
    


```python
# Peek
if stack:
    print("Top element:", stack[-1])

```

    Top element: 20
    


```python
# IsEmpty
print("Is stack empty?", len(stack) == 0)

```

    Is stack empty? False
    


```python
# Stack Length
print("Stack size:", len(stack))

```

    Stack size: 2
    


```python
# Stack function
def print_stack(s):
    for i in reversed(s):
        print(i)
print_stack(stack)

```

    20
    10
    


```python
# Push more elements
stack.append(40)
stack.append(50)
print_stack(stack)

```

    50
    40
    20
    10
    


```python
# Pop all elements
while stack:
    stack.pop()
print("Stack cleared:", stack)

```

    Stack cleared: []
    


```python
# Queue using List
queue = []

```


```python
# Enqueue
queue.append(1)
queue.append(2)
queue.append(3)
print("Queue:", queue)

```

    Queue: [1, 2, 3]
    


```python
# Dequeue
queue.pop(0)
print("After Dequeue:", queue)

```

    After Dequeue: [2, 3]
    


```python
# Is queue empty?
print("Empty?", len(queue) == 0)

```

    Empty? False
    


```python
# Peek front
if queue:
    print("Front:", queue[0])

```

    Front: 2
    


```python
# Queue Length
print("Queue size:", len(queue))

```

    Queue size: 2
    


```python
# Using deque for efficient queue
from collections import deque
dq = deque()

```


```python
dq.append(10)
dq.append(20)
dq.append(30)
print("Deque:", dq)

```

    Deque: deque([10, 20, 30])
    


```python
dq.popleft()
print("After popleft:", dq)

```

    After popleft: deque([20, 30])
    


```python
dq.appendleft(5)
print("After appendleft:", dq)

```

    After appendleft: deque([5, 20, 30])
    


```python
# Node class
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

```


```python
# Linked List class
class LinkedList:
    def __init__(self):
        self.head = None

    def insert(self, data):
        new_node = Node(data)
        if not self.head:
            self.head = new_node
        else:
            temp = self.head
            while temp.next:
                temp = temp.next
            temp.next = new_node

    def display(self):
        temp = self.head
        while temp:
            print(temp.data, end=" -> ")
            temp = temp.next
        print("None")

```


```python
ll = LinkedList()
ll.insert(1)
ll.insert(2)
ll.insert(3)

```


```python
ll.display()

```

    1 -> 2 -> 3 -> None
    


```python
# Insert at beginning
def insert_at_beginning(self, data):
    new_node = Node(data)
    new_node.next = self.head
    self.head = new_node
LinkedList.insert_at_beginning = insert_at_beginning

```


```python
ll.insert_at_beginning(0)
ll.display()

```

    0 -> 1 -> 2 -> 3 -> None
    


```python
# Delete by value
def delete(self, key):
    temp = self.head
    if temp and temp.data == key:
        self.head = temp.next
        return
    while temp.next:
        if temp.next.data == key:
            temp.next = temp.next.next
            return
        temp = temp.next
LinkedList.delete = delete

```


```python
ll.delete(2)
ll.display()

```

    0 -> 1 -> 3 -> None
    


```python
ll.delete(0)
ll.display()

```

    1 -> 3 -> None
    


```python
ll.delete(10)  # non-existent
ll.display()

```

    1 -> 3 -> None
    


```python
# Linear Search
def linear_search(arr, x):
    for i in range(len(arr)):
        if arr[i] == x:
            return i
    return -1

```


```python
arr = [5, 2, 9, 4, 7]
print("Index of 9:", linear_search(arr, 9))

```

    Index of 9: 2
    


```python
print("Index of 3 (not found):", linear_search(arr, 3))

```

    Index of 3 (not found): -1
    


```python
# Binary Search
def binary_search(arr, x):
    low, high = 0, len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == x:
            return mid
        elif arr[mid] < x:
            low = mid + 1
        else:
            high = mid - 1
    return -1

```


```python
sorted_arr = sorted(arr)
print("Sorted:", sorted_arr)

```

    Sorted: [2, 4, 5, 7, 9]
    


```python
print("Binary search 4:", binary_search(sorted_arr, 4))

```

    Binary search 4: 1
    


```python
print("Binary search 8 (not found):", binary_search(sorted_arr, 8))

```

    Binary search 8 (not found): -1
    


```python
# Edge case: empty array
print("Empty array:", binary_search([], 1))

```

    Empty array: -1
    


```python
# Edge case: one element
print("One element:", binary_search([5], 5))

```

    One element: 0
    


```python
# Binary search for negative numbers
neg_arr = [-9, -3, 0, 2, 4]
print("Find -3:", binary_search(neg_arr, -3))

```

    Find -3: 1
    


```python
# Bubble Sort
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

```


```python
data = [64, 34, 25, 12, 22, 11, 90]
bubble_sort(data)
print("Bubble Sorted:", data)

```

    Bubble Sorted: [11, 12, 22, 25, 34, 64, 90]
    


```python
# Insertion Sort
def insertion_sort(arr):
    for i in range(1, len(arr)):
        key = arr[i]
        j = i - 1
        while j >= 0 and key < arr[j]:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key

```


```python
data2 = [9, 1, 6, 3, 2]
insertion_sort(data2)
print("Insertion Sorted:", data2)

```

    Insertion Sorted: [1, 2, 3, 6, 9]
    


```python
# Selection Sort
def selection_sort(arr):
    for i in range(len(arr)):
        min_idx = i
        for j in range(i + 1, len(arr)):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i], arr[min_idx] = arr[min_idx], arr[i]

```


```python
data3 = [29, 10, 14, 37, 13]
selection_sort(data3)
print("Selection Sorted:", data3)

```

    Selection Sorted: [10, 13, 14, 29, 37]
    


```python
# Merge Sort
def merge_sort(arr):
    if len(arr) > 1:
        mid = len(arr) // 2
        L = arr[:mid]
        R = arr[mid:]
        merge_sort(L)
        merge_sort(R)
        i = j = k = 0
        while i < len(L) and j < len(R):
            if L[i] < R[j]:
                arr[k] = L[i]
                i += 1
            else:
                arr[k] = R[j]
                j += 1
            k += 1
        while i < len(L):
            arr[k] = L[i]
            i += 1
            k += 1
        while j < len(R):
            arr[k] = R[j]
            j += 1
            k += 1

```


```python
data4 = [12, 11, 13, 5, 6, 7]
merge_sort(data4)
print("Merge Sorted:", data4)

```

    Merge Sorted: [5, 6, 7, 11, 12, 13]
    


```python

```


```python
# Recursive Factorial
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)

```


```python
print("Factorial 5:", factorial(5))

```

    Factorial 5: 120
    


```python
# Fibonacci
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

```


```python
print("Fibonacci of 6:", fibonacci(6))

```

    Fibonacci of 6: 8
    


```python
# Print fibonacci series
for i in range(8):
    print(fibonacci(i), end=" ")

```

    0 1 1 2 3 5 8 13 


```python
# Recursion with sum of array
def sum_array(arr):
    if not arr:
        return 0
    return arr[0] + sum_array(arr[1:])

```


```python
print("Sum:", sum_array([1, 2, 3, 4]))

```

    Sum: 10
    


```python
# Tower of Hanoi
def hanoi(n, src, temp, dest):
    if n == 1:
        print(f"Move disk 1 from {src} to {dest}")
        return
    hanoi(n - 1, src, dest, temp)
    print(f"Move disk {n} from {src} to {dest}")
    hanoi(n - 1, temp, src, dest)

```


```python
hanoi(3, 'A', 'B', 'C')

```

    Move disk 1 from A to C
    Move disk 2 from A to B
    Move disk 1 from C to B
    Move disk 3 from A to C
    Move disk 1 from B to A
    Move disk 2 from B to C
    Move disk 1 from A to C
    


```python
# Base case edge test
print("Hanoi 1 disk:")
hanoi(1, 'X', 'Y', 'Z')

```

    Hanoi 1 disk:
    Move disk 1 from X to Z
    


```python
# Tree Node
class TreeNode:
    def __init__(self, val):
        self.left = None
        self.right = None
        self.val = val

```


```python
# Pre-order Traversal
def preorder(root):
    if root:
        print(root.val, end=' ')
        preorder(root.left)
        preorder(root.right)

```


```python
# Build a simple tree
root = TreeNode(1)
root.left = TreeNode(2)
root.right = TreeNode(3)
root.left.left = TreeNode(4)
root.left.right = TreeNode(5)

```


```python
print("Preorder traversal:")
preorder(root)

```

    Preorder traversal:
    1 2 4 5 3 


```python
# In-order
def inorder(root):
    if root:
        inorder(root.left)
        print(root.val, end=' ')
        inorder(root.right)

```


```python
print("\nInorder traversal:")
inorder(root)

```

    
    Inorder traversal:
    4 2 5 1 3 


```python
# Post-order
def postorder(root):
    if root:
        postorder(root.left)
        postorder(root.right)
        print(root.val, end=' ')

```


```python
print("\nPostorder traversal:")
postorder(root)

```

    
    Postorder traversal:
    4 5 2 3 1 


```python
# Tree Depth
def depth(root):
    if not root:
        return 0
    return 1 + max(depth(root.left), depth(root.right))

```


```python
print("\nTree Depth:", depth(root))

```

    
    Tree Depth: 3
    


```python

```


```python

```


```python

```


```python

```


```python

```


---
**Score: 70**