# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
## DATE:
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1. Start.
2. Define a variables.
3. Write a functions to perform enqueue and,display elements in Queue using array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```c
char queue[50];
int size=10,front,rear,i; 
void enqueue(char data)
{
if(rear<size)
{
if(front==-1)
{
front=0;
}
rear=rear+1; 
queue[rear]=data;
}
{
printf("%c\n",queue[i]);
}
}
void dequeue()
{
SAVEETHA ENGINEERING COLLEGE
if(front==-1||front>rear)
{
printf("Queue Underflow\n");
}
else
{
front=front+1;
}
}
void display()
{
for(i=front;i<=rear;i++)
printf(“%c “,queue[i]);
}
```

## Output:

![image](https://github.com/user-attachments/assets/7ae64bd6-2595-4be1-9f78-cedeb91ee5cc)

## Result:
Thus the program was executed and the output was verified successfully.
