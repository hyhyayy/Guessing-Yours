# Guessing-Yours
#include <iostream>
using namespace std;
int main() {
  int A, B, C, D;
  string ans;
  string input;

  cout << "Welcome to Guessing Yours !" << endl;
  cout << "Today we are gonna guessing what is your number. " << endl << endl;

  cout << "-----------------------------------------------------------" << endl
       << endl;

  cout << "Now think about a number. Any numbers." << endl;
  cout << "You don't have to let me know what is inside your head" << endl
       << endl;
  cout << "Before that, I want you to fill any numbers here" << endl << endl;
  cout << "For A numbers : ";
  cin >> A;
  cout << "For B numbers : ";
  cin >> B;
  cout << "For C numbers : ";
  cin >> C;
  cout << "For D numbers : ";
  cin >> D;

  cout << "-----------------------------------------------------------" << endl
       << endl;

  cout << "From now on, I will take all this numbers from A to D to add it "
          "with each other "
       << endl
       << endl;

  cout << "The number wil be added one by one " << endl << endl;

  cout << "By referring number here, please confirm your number again :" << endl
       << endl;

  cout << "A:" << A << ", B:" << B << ", C:" << C << ", D:" << D << "\n\n";

  cout << "Enter your A number :\t";
  cin >> A;

  cout << "Enter your B number :\t";
  cin >> B;
  ;
  cout << "Enter your C number :\t";
  cin >> C;

  cout << "Enter your D number :\t";
  cin >> D;

  cout << "-----------------------------------------------------------" << endl;

  cout << "Once you got the answer, I want you to subtract the number that you "
          "think at first "
       << endl
       << endl;

  ans = A + B + C + D;

  cout << "Then I will guess your number," << endl;
  cout << "Is it " << ans << " right ?" << endl;

  cout << "-----------------------------------------------------------" << endl;
  cout << "Thank you for playing this game !";

  return 0;
}
