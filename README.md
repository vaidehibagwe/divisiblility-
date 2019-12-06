# divisiblility-


#include <iostream> 
using namespace std; 
  

void result(int N) 
{      
    // iterate from 0 to N 
    for (int num = 0; num < N; num++) 
    {      
        // Short-circuit operator is used  
        if (num % 3 == 0 && num % 2 == 0) 
            cout << num << " "; 
    } 
} 
  

int main() 
{      
  
    int N = 100; 
      
     
    result(N); 
    return 0; 
}
