#include "stdafx.h" 
#include <iostream> 
#include <conio.h>

using namespace std;

int sum(int n) { 
                int s=0; 
                while (n != 0) { 
                                s += n % 10; 
                                n /= 10; 
                                } 
               return s; 
               }
int main()
{
         int a,b,i=0;
         cin»a»b;
         if (b>=a) cout « "error";
                            else 
{
                            for(a;a>=b;a++;){
                            if (sum(a)%5==0)i++;
}
                                               cout«"kol-vo chisel"«i;
}
_getch();
return 0;
}
