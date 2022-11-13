# MATCHING-CHARACTER



// Online C++ compiler to run C++ program online
#include <iostream>
#include <bits/stdc++.h>
using namespace std;

void count(string str1, string str2)
{
    int i=0;
    for(int i=0; i<str1.length(); i++)
    {
        if(str1[i]==str2[i+1])
        {
            printf("%d", i);
        }
    }
    return 0;
}
