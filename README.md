# cplus2whileloop.guessgame
building guessing game using while loop 

#include <iostream>
using namespace std;

int main()
{
     int secretNum=7;
     int guess;
     
     while (secretNum!=guess){
          cout<<" Enter guess: ";
          cin>>guess;
          
     }
     cout<<"you win the game!";
     
    return 0;
}
output:
  Enter guess: 80
Enter guess: 566
Enter guess: 34
Enter guess: 7
you win the game!
