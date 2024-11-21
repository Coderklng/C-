//c++ using Dsa concept
//Make cpp program and using dsa //concept to handle 
#include<iostream>
#include<unistd.h>

using namespace std;
#define MAX_SIZE 5
int top = -1;
#define MIN_SIZE 5
int queue[MIN_SIZE];
int rear=-1;
int front = -1;
int stack[MAX_SIZE];
class Stack{

   public:
   void push(int len) {
   
   if(top == MAX_SIZE - 1) {
   
     cout<<"Overflow & exit"<<endl;
   }else{
   
       ++top;
       stack[top]=len;
       
       cout<<"Inserted Elements :"<<len;
   
   }
   
   }
   
 void pop(){
 
 if(top == -1) {
 
  cout<<"Underflow & exit";
 
 }else{
 
    int item = stack[top--];
 
      cout<<"Deleted items:"<<item;
 
 }
 
 }
 
 void display()
 {
 
  if(top == -1) {
 
    cout<<"Stack is an empty"<<endl;
 }
 else{
 
   cout<<"Display elements:";
   for(int u=0;u<top;u++) {
   
     cout<<stack[u];
   
   
   
   }
 
 
 }
 
 }
 
 
   
};

class Queue{

 public:
 void Enqueue(int good) {
 
  if(rear == MIN_SIZE - 1) {
 
   cout<<"Overflow & exit"<<endl;
 
 }else{
 
   if(front == -1) { // -1 define the memory is empty 
 
     front = 0; // it define the inside one elements
     
 }
 
   ++rear; // insert 
   
   queue[rear]=good;
   cout<<"Inserted Elements:"<<good;
 
 }
 
 }
 
 void Dequeue() {
 
 if(top == -1) {
 
   cout<<"Underflow & exit"<<endl;
 
 }else {
 
 
 cout<<"Deleted Elements:"<<queue[front];
 if(front == rear) { // 0 == 2 NO 
 
    front = rear = -1;
 
 
 }else{
 
   front++; // front = 1;
   
   }
  
 
 }
 
 
 
 }
 
 void display () {
 
  if(front == -1) {
  
  
     cout<<"Queue is an empty"<<endl;
  
  }else{
 
 cout<<"Display Elements:"<<endl;
 for(int o=front;o<=rear;o++) {
 
    cout<<queue[o];
 
 
 }
 
 }
 
 
 
 }
 
 
};

class Linear{

 public:
 void Search() {
 int f;
   cout<<"Enter the number to find the location:"<<endl;
   cin>>f;
   int arr[5]={10, 20,30,40,50};
   int d=0,g=0;
   
   while(d < 5) {
   
   if(arr[d] == f) {
   
      cout<<"Elements found in this position:"<<d;
       g=1;
       break;
   
   
   }
   
   d++;
   
   }
   
   if(g == 0) {
   
   cout<<"Elements not found in this location:"<<endl;
   
   
   }
 
 
 }

};

class Binary{

public:
void dinary(){

int u, c=0,loc=0,upr=5,mid, x=0;
cout<<"Enter the elements to find the position:"<<endl;
cin>>u;
int array[5]={10, 20,30,40,50};
while(loc < upr) {

   mid = (loc+upr)/2;
  if(array[mid]==u) {

    x=1;
    break;

}if(array[mid] < u) {

  loc = mid + 1;

}else{

  upr = mid - 1;

}


}
if(x==1) {

 cout<<"Elements found in this position:"<<mid<<endl;

}else{


cout<<"Elements not found in this position:"<<endl;


}

}

};

class Bubble{

public:
void sort(int arr[],int size) {
int d;
for( d=0;d<size; ++d) {

  cin>>arr[d];

}

for(d=0;d<size-1;d++) {

    for(int y=0; y < size; y++) {
    
        if(arr[y] > arr[y+1]) {
        
        int temp = arr[y];
        arr[y]=arr[y+1];
        arr[y+1]=temp;
        
        
        }
        
        
        
    }


}

for(d=0;d<size;++d) {

  cout<<"  "<<arr[d];

}


}


};

class Selection {

public:
void sort(int arr[],int size) {

  int m,loc,s;
  for(s=0;s<size;++s) {

  cin>>arr[s];

}

for(s=0;s<size-1;s++) {

  m=arr[s];
  loc=s+1;

    for(int p=s+1;p<size;p++) {
    
      if(m > arr[p]) {
    
      m=arr[p]; // m = arr[1] < 
      loc=p; // loc=1
    
    
    }
    
    }if(arr[loc] < arr[s]) {
    
      int temp = arr[s];
      arr[s]=arr[loc];
      arr[loc]=temp;
    
    
    
    }


}

for(s=0;s<size;++s) {


   cout << "  "<<arr[s];

}


}

};

class Insertion {

 public:
 void sort(int arr[],int size) {

  int d;
  for(d=0;d<size;++d) {
  
   cin>>arr[d];
  
  
  }

for(d=1;d<size;++d) {

   for(int b=d-1; b >= 0;b--) {
   
     if(arr[b] >  arr[b+1]) {
   
       int temp = arr[b+1];
       arr[b+1]=arr[b];
       arr[b]=temp;
       
       
   
   }
   
   }




}

for(d=0;d<size;++d) {

 cout<<"  "<<arr[d];
 
 }
 
 
 
 }

};

class Checkout {

public:
string password;
string confirm;

void Loading() {

 cout<<"Loading";
 for(int c=0;c<5;c++) {

   cout<<".";
   cout.flush();
   sleep(1);



}

}
void checkIn() {

  cout<<" Enter the passsword :"<<endl;
  cin>>password;
  cout<<"Enter the confirm password:"<<endl;
  cin>>confirm;
  
  string len = password;
  
  if(len == confirm){
  
  
   Loading();
   cout<<"\nYour password is correct:"<<endl;
   
  }else{
   
   cout<<"\nYour password is incorrect:"<<endl;
   

}


}


};

int main() 
{


Checkout out;
out.checkIn();
int a[0],size;

 if(out.password == out.confirm) {
 
   cout<<"Enter the number :"<<endl;
   cin>>size;
    Insertion king;
    king.sort(a, size);
 

}

return 0;

} oops concept
