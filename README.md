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
```
//WITHOUT USING STRING:
#include <iostream>
#include <string>
using namespace std;
int main()
{
	char answer = ' ';
	cout << "Can your friend play musical instruments? Y or N? " << endl;
	cin >> answer;
	if (answer == 'y' || answer == 'Y') {
		int ch;
		cout << "What instrument does you friend play?" << endl << "1. Guitar" << endl << "2. Drums" << endl << "3. Piano" << endl << "4. Flute" << endl;
		cin >> ch;
		if (ch == 1 || ch == 2) {
			cout << "The friend can join the band.";
		}else {
			cout << "The friend cannot join the band.";
		}
	}else {
		cout << "The friend cannot join the band.";
	}
	cin >> answer;
	return 0;
} 

//WITH STRING:
```

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
