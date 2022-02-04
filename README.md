# eligibilityTovote

#include<iostream>
using namespace std;

int main()
{
    int age,i=0;
    cout<<"enter your age:";
    cin>>age;
    if(age>=18){
    cout<<"ELIGIBLE TO VOTE";}
    else
    {
     for(i=0;i<(18-age);i++)
       {
        
       }
    cout<<"WAIT FOR "<<i<<" YEAR(S) TO BE ELIGIBLE TO VOTE";
    }
    
    
    return 0;
}
