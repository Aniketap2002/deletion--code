# deletion--code
//how to delete selected number from array
#include<iostream>
using namespace std;
int size,num,i;
cout<<"Enter size of your array"
cin>>size;
int arr[size];
cout<<"enter numbers you want"
for(i=0;i<=size;i++)
{   
   cin>>arr[size] ;
}
cout<< "Enter position you want to delete";  
cin>>num;
for(i=num;i<=1;i++)
{
   arr[i]=arr[i+1];
}
for(i=1;i<=size;i++)  
{
   cout<<arr[i];
}  
return 0;
}
  
  
  
