#include<bits/stdc++.h>
using namespace std;

bool isValid(string s) {
    for(int i=2;i<s.size();i++){
        if(s[i]==s[i-1]&&s[i-1]==s[i-2])
            return true;
    }
    return false;
}

int main(){
    string name;
    cin>>name;
    if(isValid(name))
        cout<<"Accept";
    else
        cout<<"NOT Accept";
}
