# Exercise---IF-Statements

EXERCISES

SLIDE 20, It's my Birthday

    #include <iostream>
    using namespace std;

    int main()
    {
        bool myBirthday = true; 
        int age = 18;

        if (myBirthday == true) { //if birthday is true, the character output will show that it is the user's birthday along with their age
            age++;
            cout << "It is my birthday. I am " << age << " years old";
        }
        else //if birthday is NOT true, the character output will show that it is NOT their birthday
        cout << "It is not my birthday" << endl;
    }
   
SLIDE 21, Good Morning?

    #include <iostream>
    using namespace std;

    int main()
    {
        int currentTime = 3; //declare and initialise variable for time

        if (currentTime < 12) {
            cout << "It's PM" << endl; //output PM message
        }
        else //else 'currentTime' must be less than 12
        {
            cout << "It's AM" << endl;
        }
        cin.get(); //keeps console window open on Visual Studio
        return 0;
    }

SLIDE 23, Extension Problem (Optional)

    #include <iostream>
    using namespace std;
    int main()
    {
        int time; //variable
        cout << "What time is it in your part of the world? \n"; //character output
        cin >> time; //character input

        if (time <= 11) //if the number is less than or equal to 11, it is morning
        {
            cout << "\nGood Morning" << endl;
        }
        else if (time >= 12 && time <= 17) //if the number is greater than or equal to 12 and less than or equal to 17, it is afternoon
        {
            cout << "\nGood Afternoon" << endl;
        }
        else if (time >= 18 && time <= 21) //if the number is greater than or equal to 18 and less than or equal to 21, it is evening
        {
            cout << "\nGood Evening" << endl;
        }
        else if (time >= 22 && time <= 24) //if the number is greater than or equal to 22 and less than or equal to 24, it is time to sleep
        {
            cout << "\nGood Night" << endl;
        }
        else //other inputs besides 1-24
        {
            cout << "\nTime given not valid";
        }
        return 0;
    }
    
SLIDE 23, Can I vote?

    #include <iostream>
    using namespace std;

    int main()
    {
        int age = 17; //variable
            if (age >= 18) { //if age is more than or equal to 18, the user can vote
                cout << "You can vote" << endl;
            }
            else //but since the variable inputted is age: 17, the user cannot vote
            {
                cout << "You can not vote" << endl;
            }
            cin.get(); //cin meaning character input and get() is used for accessing character array
            return 0;
    }

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
  
