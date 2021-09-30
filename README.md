# MARK MY WORDS
```
#include <iostream>
using namespace std;
int main()
{
    char again = 'y';
    while (again == 'y' || again == 'Y') {
        int a;
        cout << "Enter your grade: " << endl;
        cin >> a;
        if (a >= 70)
            cout << " Your grade is A Above 70%" << endl;
        else if (a <= 69 && a >= 60)
            cout << " Your grade is B 60-69%" << endl;
        else if (a <= 59 && a >= 50)
            cout << " Your grade is C 50-59%" << endl;
        else if (a <= 49 && a >= 40)
            cout << " Your grade is D 40-49%" << endl;
        else if (a <= 39)
            cout << " Your grade is F Below 40%" << endl;      
    }
    cout << "Go again? (Y or N): ";
    cin >> again;
    return 0;
}
```
# STARTING A BAND
