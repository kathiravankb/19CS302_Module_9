# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
## DATE: 5/5/2025
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to traverse the linked list and display it in the following format. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End

## Program:
```
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void display() 
{ 
struct Node *temp; 
temp=head; 
while(temp!=NULL) 
{ 
printf("%c\n",temp->data); 
temp=temp->next; 
} 
 
} 
```

## Output:
![image](https://github.com/user-attachments/assets/fcb3b6e5-e980-44f4-a1fd-b276d6b1478f)

## Result:
Thus the program was executed and the output was verified successfully.
