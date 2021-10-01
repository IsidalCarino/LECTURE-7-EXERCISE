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
// WORK IN PROGRESS SLIDE 17 TO 20

# KILLING TIME
```
#include <iostream>
using namespace std;
int main()
{
	int minute;
	int money;
	cout << "When will your friend arrive? (Enter how many minutes) " << endl;;
	cin >> minute;
	if (minute >= 15)
	{
		cout << "Hmm.. gotta wait then.. Do I have money for coffee? (Check your wallet how much money you have left and enter the amount)" << endl;
		cin >> money;
		if (money > 5)
		{
			cout << "I have money for coffee, I'll go buy and drink while waiting." << endl;
		}else{
			cout << "a... I don't see any money here. I'll just walk around and wait for my friend and ask him/her to buy me coffee." << endl;
		}
	}else{
		cout << "a... I'll wait for him/her at the food zone." << endl;
	}
	return 0;
}
```
