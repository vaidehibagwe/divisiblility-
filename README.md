# divisiblility-


#include <iostream> 
using namespace std; 
  

void result(int N) 
{      
       for (int num = 0; num < N; num++) 
    {      
        
        if (num % 3 == 0 && num % 2 == 0) 
            cout << num << " "; 
          
    } 
} 
  

int main() 
{      
  
    int N = 100; 
      
    cout << "Numbers divisible by 6" ;
    result(N); 
    return 0; 
}
