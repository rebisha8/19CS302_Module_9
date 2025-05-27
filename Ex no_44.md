# EX 44 C functions to perform enqueue, dequeue, display, peek in Queue using Array.
## DATE:
## AIM:
To write a C Write a functions to perform enqueue, dequeue, display, peek in Queue using Array.

## Algorithm
1. Start.
2. Define a variables.
3. Write a functions to perform enqueue,dequeue ,display,peek in Queue using array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End 

## Program:
```c
char queue[50];
int size=10,front,rear,i; 
void enqueue(char data)
{if(rear<size){
if(front==-1){
front=0;
}rear=rear+1; queue[rear]=data;
}{
printf("%c\n",queue[i]);
}
}
void dequeue()
{
if(front==-1||front>rear){
printf("Queue Underflow\n");
}
else
{
front=front+1;
SAVEETHA ENGINEERING COLLEGE
}
}
void display()
{
for(i=front;i<=rear;i++)
printf(“%c “,queue[i]);
}
void peek()
{
printf("%c\n",queue[front]);
}
}
```

## Output:
![image](https://github.com/user-attachments/assets/e5b338a6-451a-4a02-b820-d9c01dd382bb)


## Result:
Thus the program was executed and the output was verified successfully.
