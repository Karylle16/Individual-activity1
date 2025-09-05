#include <iostream>
#include <string>

using namespace std;

int main() {
    string fullName, courseYearSec, birthday, motto;

    //Input
    cout<< "Hi! I'm ";
    
    cout << "Karylle Czyra S. Rinonos ";
    getline(cin, fullName);

    cout << "BSIT, 2J. ";
    getline(cin, courseYearSec);
    
    cout<< "Welcome to Data Structures and Algorithm! ";
    
    cout<< "My Birthday is on ";
    getline(cin, birthday);

    cout << "June, 16 2006. ";
    getline(cin, birthday);
    
    cout<< "and my motto/motivation in life ";
    getline(cin, motto);

    cout << "Keep Learning Until you Succes! ";
    getline(cin, motto);

    
    return 0;
}

   //output
   Hi! I'm Karylle Czyra S. Rinonos BSIT, 2J. Welcome to Data Structures and Algorithm! My Birthday is on June, 16 2006. and my motto/motivation in life Keep Learning Until you Succes! 
