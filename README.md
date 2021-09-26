# Exercise---IF-Statements
C++ Basic Exercise

SLIDE 24, Odd or Even
    #include <iostream>
    using namespace std;

    int main()
    {
    int number, remainder;

    cout << "Enter the number: ";
    cin >> number;
    remainder = number % 2;
    if (remainder == 0)
        cout << number << " is an EVEN number" << endl;
    else
        cout << number << " is an ODD number" << endl;
    return 0;
    }
  
  SLIDE 25, Number Checker
 
    #include <iostream>
    using namespace std;

    int main()
    {
        int num;
        cout << "Enter the number to be checked: ";
        cin >> num;
        if (num >= 0)
            cout << num << " is a POSITIVE number.";
        else
            cout << num << " is a NEGATIVE number.";

    return 0;
    }
  
 SLIDE 26, Profit or Loss
 
    #include <iostream>
    using namespace std;

    int main()
    {
        int pp, sp, profit, loss;
        cout << "Purchase price: ";
        cin >> pp;
        cout << "Sale price: ";
        cin >> sp;
        if (sp > pp)
        {
            profit = sp - pp;
            cout << "Purchase Price = " << profit << endl;
        }
        else if (pp > sp)
     {
            loss = pp - sp;
            cout << "Loss = " << loss << endl;
     }
        else
     {
     cout << "No profit, No loss.";
     }
    }
  
SLIDE 27, Name that Shape

    #include <iostream>
    using namespace std;

    int main()
    {
        int number;
        cout << "Enter the number of sides: ";
        cin >> number;
        if (number == 0)
            printf("The shape is CIRCLE");
        else if (number == 3)
            printf("The shape is TRIANGLE");
        else if (number == 4)
            printf("The shape is QUADRILATERAL");
        else if (number == 5)
            printf("The shape is PENTAGON");
        else if (number == 6)
            printf("The shape is HEXAGON");
        else if (number == 7)
            printf("The shape is HEPTAGON");
        else if (number == 8)
            printf("The shape is OCTAGON");
        else if (number == 9)
            printf("The shape is NONAGON");
        else if (number == 10)
                printf("The shape is DECAGON");
        else
            printf("No shape exist of these sides");


    }
  
