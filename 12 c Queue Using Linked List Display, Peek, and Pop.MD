# 12 c Queue Using Linked List – Display, Peek, and Pop

## Aim

To write a Python program to insert elements into a queue and check whether the queue is full or not.


## Algorithm

1. Start
2.Define a maximum size for the queue .
3.Initialize an empty queue.
4.Insert elements into the queue using a loop.
5.After each insertion, or at the end, check:
     If the length of the queue is equal to the maximum size → Queue is Full.
     Else → Queue is Not Full.
6.Display the queue status.
7.End

## Program
Reg no: 212222040177
Name: Venkatesan M

```
from queue import Queue

queue = Queue(maxsize = 4)

queue.put('a')
queue.put('b')
queue.put('c')

if queue.full():
    print("Queue is full")
else:
    print("Queue is not full")
```

## OUTPUT
![Screenshot 2025-05-12 223016](https://github.com/user-attachments/assets/20704950-d3b9-4682-8d17-6075d9b32caa)



## RESULT
Result: Thus, the given program is implemented and executed successfully .
