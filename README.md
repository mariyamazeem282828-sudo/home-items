# home-items
#include <iostream>
using namespace std;
int main()
{
    int choice, status;

    cout << "HOME ITEMS CONTROL SYSTEM" << endl;
    cout << "1. Fan" << endl;
    cout << "2. Light" << endl;
    cout << "3. Refrigerator" << endl;
    cout << "4. Air Conditioner" << endl;
    cout << "5. Television" << endl;

    cout << "\nEnter your choice (1-5): ";
    cin >> choice;

    cout << "Enter 1 to ON or 0 to OFF: ";
    cin >> status;

    if (choice == 1)
    {
        if (status == 1)
            cout << "Fan is ON. Cooling the room." << endl;
        else
            cout << "Fan is OFF. Electricity saved." << endl;
    }
    else if (choice == 2)
    {
        if (status == 1)
            cout << "Light is ON. Room is bright." << endl;
        else
            cout << "Light is OFF. Electricity saved." << endl;
    }
    else if (choice == 3)
    {
        if (status == 1)
            cout << "Refrigerator is ON. Food is cooling." << endl;
        else
            cout << "Refrigerator is OFF. Food may spoil." << endl;
    }
    else if (choice == 4)
    {
        if (status == 1)
            cout << "AC is ON. Room is cold." << endl;
        else
            cout << "AC is OFF. Power saved." << endl;
    }
    else if (choice == 5)
    {
        if (status == 1)
            cout << "TV is ON. Enjoy watching." << endl;
        else
            cout << "TV is OFF. Screen is closed." << endl;
    }
    else
    {
        cout << "Invalid choice!" << endl;
    }

    return 0;
}
