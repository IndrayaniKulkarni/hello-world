# hello-world
First time creating the repository for daily practice
#include<iostream>
using namespace std;
/*.
* * * *
* * * *
* * * *
* * * *
int r,c;
    cin>>r>>c;
    for(int j=0;j<r;j++)
    {
      for(int i=0;i<c;i++)
       {
         cout<<" "<<"*";
       }
      cout<<"\n";
    }
*/

/*Q.2 Hollow rectangle
* * * *
*     *
*     *
* * * *
int r,c;
    cin>>r>>c;
    for(int i=1;i<=r;i++)
    {
        for(int j=1;j<=c;j++)
        {
            
            if(i==1 || i==r || j==1 || j==c)
            {
                cout<<"*";
            }  
           
            else 
            {
                cout<<" ";
            }
            
        }
        cout<<endl;
    }
*/

/*
****
***
**
*
int n;
    cin>>n;
    for(int i=n;i>=0;i--)
    {   
        for(int j=1;j<=i;j++)
        {
            cout<<" * ";
        }
       cout<<endl;
    }
*/

/*
               *
              ** 
             *** 
            **** 
           *****  
int n;
    cin>>n;
    for(int i=1;i<=n;i++)
    {   
        for(int j=1;j<=n;j++)
        {
            if(j<=n-i)
            {
                cout<<" ";
            }
            else
            {
                cout<<"*";
            }
            
            
        } 
        cout<<endl;
    }
*/

/* Half pyramid using numbers
1
22
333
4444
int n;
    cin>>n;
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=i;j++)
        {
            cout<<i<<" ";
        }
        cout<<endl;
    }
*/

/*
Flyod's triangle
1 
2 3
4 5 6
7 8 9 10
11 12 13 14 15
int n;
    cin>>n;
    int num=1;
    for(int i=1;i<=n;i++)
    {
        for(int j=0;j<i;j++)
        {
            cout<<num<<" ";
            num++;
        }
        cout<<endl;
    }
*/

/* Butterfly
*      *
**    **
***  ***
********
********
***  ***
**    **
*      *
 int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=i;j++)
        {
            cout<<"*"; 
             
        }
        int var=2*(n-i);//for spaces 
        for(int k=1; k<=var; k++)
            {
                cout<<" ";
            }
        for(int j=1;j<=i;j++)
        {
            cout<<"*"; 
             
        }    
        cout<<endl;
    }
     for(int i=n;i>=0;i--)
    {
        for(int j=1;j<=i;j++)
        {
            cout<<"*"; 
             
        }
        int var=2*(n-i);//for spaces 
        for(int k=1; k<=var; k++)
            {
                cout<<" ";
            }
        for(int j=1;j<=i;j++)
        {
            cout<<"*"; 
             
        }    
        cout<<endl;
    }
*/

/* 
1 2 3 4 5
1 2 3 4
1 2 3 
1 2
1
 int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n+1-i;j++)
        {
            cout<<j<<" "; 
             
        }
        cout<<endl;
    }
*/

/*
1
0 1
1 0 1
0 1 0 1
1 0 1 0 1

int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=i;j++)
        {
            /*if(((i+j)%2)==0)
            {
                cout<<" 1";
            }
             else
             {
                 cout<<" 0";
             }*/
//             cout<<((i+j)%2==0)?1:0;//use of teranry operator - (condition)?ifTrue:ifFalse
 //       }
 //       cout<<endl; */

/*
    *****
   *****
  *****
 *****
*****
 int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        
            for(int k=1; k<=n-i; k++)
            {
                cout<<" ";
            }
            for(int m=1; m<=n; m++)
            {
                cout<<"*";
            }
            
        
        cout<<endl;
    } 

*/

/*
    1 
   1 2
  1 2 3
 1 2 3 4
1 2 3 4 5
 int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        
            for(int k=1; k<=n-i; k++)
            {
                cout<<" ";
            }
            for(int m=1; m<=i; m++)
            {
                cout<<m<<" ";
            }
            
        
        cout<<endl;
    }  
*/

/*
          1
        2 1 2
      3 2 1 2 3
    4 3 2 1 2 3 4
  5 4 3 2 1 2 3 4 5
6 5 4 3 2 1 2 3 4 5 6
int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
            int k;
            for(k=1; k<=n-i; k++)
            {
                cout<<"  ";
            }
            int num=i;
            for(;k<=n; k++)
            {
                cout<<num--<<" ";
            }
            num=2;
            for(;k<=n+i-1; k++)
            {
                cout<<num++<<" ";
            }
        cout<<endl;
    }    
        
*/

/*    
      *
    * * *
  * * * * * 
* * * * * * *
* * * * * * *
  * * * * * 
    * * *
      * 
int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {  
            for(int k=1; k<=n-i; k++)
            {
                cout<<" ";
            }
            
            for(int k=1;k<=2*i-1; k++)
            {
                cout<<"*";
            }   
        cout<<endl;
    }
    for(int i=n;i>=1;i--)
    {
            
            for(int k=1; k<=n-i; k++)
            {
                cout<<" ";
            }
            
            for(int k=1;k<=2*i-1; k++)
            {
                cout<<"*";
            }   
        cout<<endl;  
      
    } 
*/

/*
  *   *
 * * * *
*   *   *
int n;
    cin>>n;
    
    for(int i=1;i<=3;i++)
    {  
            for(int k=1;k<=n; k++)
            {
               if((i+k)%4==0||(i==2 && k%4==0) )
               { 
                   cout<<"*";
               } 
               else{
                   cout<<" ";
               }  
            }   
        cout<<endl;
    } 
*/

/*
Practice question
*
**
***
****
*****
******

    int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {  
            for(int k=1;k<=i; k++)
            {  
              cout<<"*";   
            }   
        cout<<endl;
    } 
*/
int main()
{  
    int n;
    cin>>n;
    
    for(int i=n;i>=1;i--)
    {  
            for(int k=1;k<=i; k++)
            {  
              cout<<"*";   
            }   
        cout<<endl;
    } 
        
    return 0;
}
