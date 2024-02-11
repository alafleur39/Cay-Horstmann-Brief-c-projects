#include <iostream>
#include <string>
using namespace std;

/*
Writeaprogramthattranslatesalettergradeintoanumbergrade.Lettergradesare A, B, C, D, and F, 
possibly followed by + or –. 
Their numeric values are 4, 3, 2, 1, and 0. 
There is no F+ or F–. A + increases the numeric value by 0.3, a – decreases it by 0.3. 
However, an A+ has value 4.0.
*/

// project 3.1 in c++ text cay hortsmann
int main()
{
    cout << "Letter Range A B C D E F this includes minuses and plus grades ex: A+ or B-" << endl;
    
    cout << "Enter a letter grade: ";
    string letter_grade;
    cin >> letter_grade;

    double A_plus, A_minus, A;
    double B_plus, B_minus, B;
    double C_plus , C_minus, C;
    double D_Plus , D_minus, D;
    double f;

    if (letter_grade=="A+")
    {
        A_plus = 4.0;
        cout << "Enter a letter grade: "<<A_plus;
    }
    
     else if (letter_grade=="A")
    {
        A= 4.0;
        cout << "Enter a letter grade: "<<A;
    }

     else if (letter_grade=="A-")
    {
        A_minus = 3.7;
        cout << "Enter a letter grade: "<<A_minus;
    }

     else if (letter_grade=="B+")
    {
        B_plus = 3.3;
        cout << "Enter a letter grade: "<<B_plus;
    }

    else if (letter_grade=="B")
    {
        B = 3;
        cout << "Enter a letter grade: "<<B;
    }

    else if (letter_grade=="B-")
    {
        B_minus = 2.7;
        cout << "Enter a letter grade: "<<B_minus;
    }

    else if (letter_grade=="C+")
    {
        C_plus = 2.3;
        cout << "Enter a letter grade: "<<C_plus;
    }
    else if (letter_grade=="C")
    {
        C = 2.0;
        cout << "Enter a letter grade: "<<C;
    }
    else if (letter_grade=="C-")
    {
        C_minus = 1.7;
        cout << "Enter a letter grade: "<<C_minus;
    }
    else if (letter_grade=="D+")
    {
        D_Plus = 1.3;
        cout << "Enter a letter grade: "<<D_Plus;
    }
    else if (letter_grade=="D")
    {
        D= 1.0;
        cout << "Enter a letter grade: "<<D;
    }
    else if (letter_grade=="D-")
    {
        D_minus = 0.7;
        cout << "Enter a letter grade: "<<D_minus;
    }
    else if (letter_grade=="F")
    {
        f = 0;
        cout << "Enter a letter grade: "<<f;
    }
    

    


    


    


    


    









}
