# My-cpp
my cpp work

#include <iostream>

using namespace std;

int main()

//A function that takes two values and return their sum
/*{
    int x=2;
    int y=4;
    int sum= x+y ;
    cout<<"The sum of x and y is : "<<sum<<endl;

    int a=0;
    int b=0;


     cout<<"enter the value of a : "<<endl;
     cin>>a;
     cout<<"enter the value of b : "<<endl;
     cin>>b;
     int isum =a+b ;
     cout<<"The sum of a and b is : "<<isum<<endl;
}*/

//A function to get student number and student grades, if grades is greater than 39 print student number Followed by Pass

/*{
    int studentNumber= 0;
    int grades= 0;

    cout<<"Enter your student number : "<<endl;
    cin>>studentNumber;
    cout<<"Enter your grades : "<<endl;
    cin>> grades;

    if(grades>39){
        cout<<studentNumber<<" "<<"Pass"<<endl;
    }
    else if(grades< 39){
        cout<<studentNumber<<" "<<"Failed"<<endl;
    }
    else{
        cout<<"Please go consult with your lectures"<<endl;
    }
}*/

//2.	Create a program that consists of the following:
//To allow numbers between 8 and 17 inclusive

/*{
    int num=0;

    cout<<"Please enter any number between 8 and 17 :"<<endl;
    cin>>num;

    if(num>=8 && num<=17){
        cout<<"Thank you!!!"<<endl;

    }

    else {
        cout<<"Please re-enter your number"<<endl;
    }
}*/

//2.2	Print the third letter of the word CHRIS as requested by a user

/*{
    string name[]={"c","h" ,"r", "i" ,"s" };

    cout<<"The third letter is : "<<name[2]<<endl;

    string chris_word = "CHRIS";
    char third_letter = chris_word[2]; // Index 2 corresponds to the third letter
    cout << "The third letter of the word CHRIS is: " << third_letter << endl;

}*/

//2.3	To find the sum of all even number from 10 to 30

/*{
    int sum=0;

    for(int i=10 ; i<=30 ; i++){
      if (i % 2 == 0) {
            sum += i;
    }
    }
    cout<<"The sum of even numbers from 10 to 30 is : "<<sum<<endl;
}*/

//3.1	To determine if a number is even or odd

/*{
    int num;
     cout<<"Please enter any number : "<<endl;
     cin>>num;

     if(num%2==0 ){
        cout<<"Number enterd is even!!"<<endl;
     }
     else{
        cout<<"Number entered is odd!!"<<endl;
     }
}*/

//3.2	Sum the Odd integers between 1 and 20

/*{
    int sum=0;

    for(int i=1; i<=20 ;i++){
        if(i%2){
            sum+= i;
        }
    }
    cout<<"The sum of off integers from 1 to 20 is : "<<sum<<endl;
}*/

//4.	A program that will print the second letter of the word named SCOB as requested by a user

/*{
    string word;
    cout << "Please enter the word 'SCOB': ";
    cin >> word;

    // Check if the entered word is "SCOB"
    if (word == "SCOB") {
        // Print the second letter of the word
        char second_letter = word[1]; // Index 1 corresponds to the second letter
        cout << "The second letter of the word 'SCOB' is: " << second_letter << endl;
    } else {
        cout << "You did not enter the word 'SCOB'. Please try again." << endl;
    }
}*/

//ARRAYS

//1.1	What is the syntax for declaring a one-dimensional array in c++.
/*{
  data_type array_name[array_size]
}*/

//1.2	Declare an array with four elements.

/*{
    int elements[4];
}*/

//1.3	Declare an array of type string consisting of four elements.

/*{
    string elements[4];
}*/


//1.4	Declare array of type int with four elements and initialize it

/*{
    int elements[4]= {1,3,5, 7} ;
}*/

//1.5	Given the list A {5, 9, 3, 7} create C++ array consisting of all elements in A

/*{
    int list_A[4] = { 5, 9 , 7};
    for(int i: list_A){
        cout<<i<<"\n" ;
    }

}*/

//1.6	Develop a program to prompt the user to initialize arrays elements, Note: The array is of type string and array size 5.


/*{
    const int ARRAY_SIZE = 5; // Define the size of the array
    string names[ARRAY_SIZE];  // Declare an array of strings

    // Prompt the user to enter the array elements
    cout << "Please enter " << ARRAY_SIZE << " names:" << endl;
    for (int i = 0; i < ARRAY_SIZE; i++) {
        cout << "Enter name " << (i + 1) << ": ";
        getline(cin, names[i]); // Read the string input
    }

    // Display the entered names
    cout << "\nYou entered the following names:" << endl;
    for (int i = 0; i < ARRAY_SIZE; i++) {
        cout << "Name " << (i + 1) << ": " << names[i] << endl;
    }
}*/

//1.7	Given the array list {7, 11, 13, 17} print elements using a for loop.

/*{
    int list[4]= {7, 11, 13, 17};

    for(int i : list){

        cout<<i<<endl;
    }
}*/

//1.8	Given the array list {0, 11, 13, 17} print elements using a while loop.

/*{
    int list[]= {0, 11, 13, 17};
    int i=0;
    while(i<4){
        cout<<list[i]<<endl;
        i++;
    }
}*/

//1.9	Given the array list {“Mathebula, “Emmanuel”, “Nkateko”, ”Cheeble”} print elements using a for loop  and while loop

/*{
    string names[]={"Mathebula", "Emmanuel", "Nkateko", "Cheeble"};

    cout<<"Array list using while loop: "<<endl;
    int i=0;
    while(i<4){
        cout<<names[i]<<endl;
        i++;
    }
    cout<<"Array list using for loop : "<<endl;
    for(string names :names){
        cout<<names<<endl;
    }
}*/



/*{
   int myNumbers[5] ={3,43,12,65,9};
   for(int i: myNumbers){
    cout<<i<<"\n" ;
   }

   string names[3] ={"jabu" ,"joy" , "james" };
   for(string names :names){
    cout<<names<< "\n" ;
   }
    return 0;
}*/
