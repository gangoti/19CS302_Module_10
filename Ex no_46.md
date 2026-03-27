# EX 46 C function to traverse the linked list and display it in the following format.

## AIM:
To write a C function to traverse the linked list and display it in the following format.

## Algorithm

Start. Define a variables. Write a function to insert a node in a linked list. Read the value using scanf. Ask the user to make an input. Print out the answer. End
## Program:
```
/*
C function to traverse the linked list and display it in the following format.
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void insert(char data) 
{ 
struct Node *n=(struct Node*)malloc(sizeof(struct Node)); 
struct Node*temp; 
if(head==NULL) 
{ 
head=n; 
n->data=data; 
n->next=NULL; 
temp=head; 
return; 
} 
 
}  
else 
{ 
while(temp->next!=NULL) 
{ 
temp=temp->next; 
} 
n->next=NULL; 
n->data=data; 
temp->next=n; 
} 
}
*/
```

## Output:

<img width="1101" height="521" alt="image" src="https://github.com/user-attachments/assets/24b24211-8612-40d1-9814-433488761a79" />


## Result:
Thus the program was executed and the output was verified successfully.
