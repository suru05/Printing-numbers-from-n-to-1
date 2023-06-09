# Printing-numbers-from-n-to-1
#include <iostream>
using namespace std;
int i = 0;
void Name(int i, int N)
{
    
    if (i < N) {
        return;
    }
    cout << i << endl;
        Name(i -1, N);
    
    
}
int main()
{ 
    
    Name(35,1);
    return 0;
}
