#include <iostream>
using namespace std;
int main(){
    int input = 0;
    while(true){
        cout<<"Enter passcode: ";
        cin>>input;
        if(input == 246) break;
        else{
            cout<<"Incorrect passcode!\n";
        }
    }
    cout<<"Correct!\n";
    return 0;
}
