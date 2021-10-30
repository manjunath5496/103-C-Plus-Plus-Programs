
# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>

using namespace std;

int main()
{
   cout<<"Hello World!";

    return 0;
}

```
----------------------------------------

# Question 2

### **Question:**

> ***Write a program to Find Sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, sum;
    
    cout << "Enter two numbers : ";
    cin >> num1 >> num2;

    sum = num1 + num2;

    cout << num1 << " + " <<  num2 << " = " << sum;     

    return 0;
}
	
```
----------------------------------------

# Question 3

### **Question:**

> ***Write a program to Find Difference of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, difference;
    
    cout << "Enter two numbers : ";
    cin >> num1 >> num2;

    difference = num1 - num2;

    cout << num1 << " - " <<  num2 << " = " << difference;     

    return 0;
}
	
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to Find Division of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, division;
    
    cout << "Enter two numbers : ";
    cin >> num1 >> num2;

    division = num1 / num2;

    cout << num1 << " / " <<  num2 << " = " << division;     

    return 0;
}
```
----------------------------------------


# Question 5

### **Question:**

> ***Write a program to Calculate Area and Circumference of Circle.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <iostream>
using namespace std;
  
#define PI 3.141
  
int main(){
    float radius, area, circumference;
    cout << "Enter radius of circle : \n";
    cin >> radius;
    circumference = 2*PI*radius;
    area = PI*radius*radius;
    cout << "Circumference of circle : " << circumference <<endl;
    cout << "Area of circle : " << area <<endl;
      
    return 0;
}
	
```
----------------------------------------


# Question 6

### **Question:**

> ***Write a program to Calculate Area of Rectangle.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
  
int main(){
    
    float length, breadth, area;
    cout << "Enter the Length of a Rectangle : \n";
    cin >> length;
    cout << "Enter the Breadth of a Rectangle : \n";
    cin >> breadth;
    area = length*breadth;
    cout << "Area of Rectangle : " << area;
      
    return 0;
}
```
----------------------------------------



# Question 7

### **Question:**

> ***Write a program to Calculate Area of Parallelogram.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
  
int main(){
    
    int height;
    int base;
	long area;
    cout << "Enter the height of a Parallelogram : \n";
    cin >> height;
    cout << "Enter the Base of a Parallelogram : \n";
    cin >> base;
   	area = height*base;
    cout << "Area of Parallelogram : " << area;
      
    return 0;
}
	
```
----------------------------------------


# Question 8

### **Question:**

> ***Write a program to Calculate Area of Trapezoid.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
  
int main(){
    
    int height;
    int base1,base2;
	long area;
    cout << "Enter the Height of a Trapezoid : \n";
    cin >> height;
    cout << "Enter the Base 1 value : \n";
    cin >> base1;
    cout << "Enter the Base 2 value : \n";
    cin >> base2;
    area = (height/2)*(base1+base2);
    cout << "Area of Trapezoid : " << area;
      
    return 0;
}
```
----------------------------------------


# Question 9

### **Question:**

> ***Write a program to Calculate Volume of Cube.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

    int main()
    {
    	int side;
    	float volume;
        cout<<" Enter the side of cube : ";
    	cin>>side;
    	volume=(side*side*side);
        cout<<" The volume of a cube is : "<< volume;
     
        return 0;
    }


```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to Calculate Volume of Cylinder.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

    int main()
    {
    	const float PI = 3.141592;  
        float radius, height, volume;  
        cout<<" Enter Radius of the Cylinder \n ";
    	cin>>radius;
    	cout<<" Enter Height of the Cylinder \n  ";
    	cin>>height;
    	volume = PI * radius * radius * height; 
        cout<<" Volume of Cylinder is : "<< volume;
     
        return 0;
    }
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program to Calculate Area of an Ellipse.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
#define PI 3.141592
    int main()
    {
    	float major, minor, area;
        cout<<" Enter length of major axis: \n ";
    	cin>>major;
    	cout<<" Enter length of minor axis: \n  ";
    	cin>>minor;
    	area = PI * major * minor;
        cout<<" Area of an ellipse = "<< area;
     
        return 0;
    }

```
----------------------------------------


# Question 12

### **Question:**

> ***Write a program to Find Size of Int Float Double and Char data types.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    cout << "Size of char: " << sizeof(char) << " byte" << endl;
    cout << "\nSize of int: " << sizeof(int) << " bytes" << endl;
    cout << "\nSize of float: " << sizeof(float) << " bytes" << endl;
    cout << "\nSize of double: " << sizeof(double) << " bytes" << endl;

    return 0;
}

```
----------------------------------------

# Question 13

### **Question:**

> ***Write a program to Multiply 2 Numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    double first, second, product;

    cout << "Enter First number : ";
    cin >> first;
    cout << "\nEnter Second number : ";
    cin >> second;

    product = first * second;

    cout << "\nProduct of 2  Numbers [ "<<first<<" x "<<second<<" ] = " << product<<"\n";

    return 0;
}

```
----------------------------------------

# Question 14

### **Question:**

> ***Write a program to Display ASCII Value of a Character.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
     char b;

     cout << "Enter a Character : ";
     cin >> b;

     cout << "\nThe ASCII Value of Character [ "<< b << " ] is : " << int(b)<<"\n";

     return 0;
}
```
----------------------------------------

# Question 15

### **Question:**

> ***Write a program to Find Sum and Average of 3 numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
    float a,b,c,sum,avg;
    cout<<"Enter First number : ";
    cin>>a;
    cout<<"\nEnter Second number : ";
    cin>>b;
    cout<<"\nEnter Third number : ";
    cin>>c;

    sum=a+b+c;

    avg=sum/3;

    cout<<"\nThe Sum of 3 Numbers [ "<<a<<" + "<<b<<" + "<<c<<" ] = "<<sum<<"\n";
    cout<<"\nThe Average of 3 Numbers [ "<<a<<", "<<b<<", "<<c<<" ] = "<<avg<<"\n";

    return 0;
}
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to find Square Root of a number using Library function.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<math.h>

using namespace std;

int main()
{
    float sq,n;

    cout<<"Enter a positive number : ";
    cin>>n;

    sq=sqrt(n);

    cout<<"\nSquare root of the Entered Number [ "<<n<<" ] is : "<<sq<<"\n";

    return 0;
}
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to Find whether the entered Number is Odd or Even.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>

using namespace std;

int main()
{
    int a;
    cout<<"Enter a positive number : ";
    cin>>a;

    if(a%2==0)
    {
       cout<<"\nThe Entered Number [ "<<a<<" ] is Even.\n";
    }

    else
    {
        cout<<"\nThe Entered Number [ "<<a<<" ] is Odd.\n";
    }

    return 0;
}
```
----------------------------------------


# Question 18

### **Question:**

> ***Write a program to Find Cube of a Number using MACROS.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

#define CUBE(n) (n*n*n)

int main()
{
    int n,cube;

    cout<<"Enter a positive number : ";
    cin>>n;

    cube=CUBE(n);

    cout<<"\nThe Cube of Entered Number [ "<<n<<" ] is : [ "<<cube<<" ]\n";

    return 0;
}

```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to compute Average of 3 subjects and find percentage.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
        int mark[3], i;
        float sum=0;
        cout<<"\nEnter marks obtained in Physics, Chemistry, Maths : \n";
        for(i=0; i<3; i++)
        {
            cout<<"\nEnter mark[ "<<i+1<<" ] : ";
                cin>>mark[i];
                sum=sum+mark[i];
        }

        float avg=sum/3;
        float percentage;
        percentage=(sum/300)*100;
        cout<<"\nAverage Marks of 3 Subjects = [ "<<avg<<" ] \n";
        cout<<"\nPercentage obtained = [ "<<percentage<<"% ] \n";

        return 0;
}



```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to Find Grade of a Student.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
        int mark[3], i;
        float sum=0,avg;

        cout<<"\nEnter Marks in 3 subjects : \n";
        for(i=0; i<3; i++)
        {
            cout<<"\nEnter Marks[ "<<i+1<<" ] : ";
                cin>>mark[i];
                sum=sum+mark[i];
        }

        avg=sum/3;

        cout<<"\nGrade obtained : ";
        if(avg>80)
        {
                cout<<"[ A ]\n";
        }
        else if(avg>60 && avg<=80)
        {
                cout<<"[ B ]\n";
        }
        else if(avg>40 && avg<=60)
        {
                cout<<"[ C ]\n";
        }
        else
        {
                cout<<"[ D ]\n";
        }

        return 0;
}


```
----------------------------------------


# Question 21

### **Question:**

> ***Write a program to Find Largest of 3 numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{

    int a, b, c;
    cout <<"Enter First number : ";
    cin>>a;
    cout <<"\nEnter Second number : ";
    cin>>b;
    cout <<"\nEnter Third number : ";
    cin>>c;

    if(a>=b && a>=c)
    {
    cout<<"\nThe Largest number among [ "<<a<<", "<<b<<", "<<c<<" ] is : "<<a<<"\n";
    }
    if(b>=a && b>=c)
    {
    cout<<"\nThe Largest number among [ "<<a<<", "<<b<<", "<<c<<" ] is : "<<b<<"\n";
    }
    if(c>=a && c>=b)
    {
    cout<<"\nThe Largest number among [ "<<a<<", "<<b<<", "<<c<<" ] is : "<<c<<"\n";
    }

   return 0;
}

```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to Print Multiplication Table of a entered number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
    int i,n,x=1;

    cout<<"Enter a positive number : ";
    cin>>n;

    cout<<"\nMultiplication Table of a entered number [ "<<n<<" ] : \n\n";
    for(i=1;i<=10;i++)
    {
        x=n*i;
        cout<<"\t"<<n<<" x "<<i<<" = "<<x<<"\n\n";
    }

    return 0;
}


```
----------------------------------------


# Question 23

### **Question:**

> ***Write a program to Display all Factors of a Number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main() {
    int n, i;

    cout << "Enter a number : ";
    cin >> n;

    cout << "Factors of " << n << " : "<< endl;  
    for(i = 1; i <= n; i++) {
        if(n % i == 0)
            cout << i << " " <<endl;
    }

    return 0;
}

```
----------------------------------------


# Question 24

### **Question:**

> ***Write a program to Find the Frequency of a Character in a String.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    string str = "C++ is a general-purpose programming language.";
    char c = 'a';
    int count = 0;

    for (int i = 0; i < str.size(); i++)
    {
        if (str[i] ==  c)
        {
            count ++;
        }
    }

    cout << "Frequency of alphabet " << c << " in the string is: " << count;

    return 0;
}


```
----------------------------------------

# Question 25

### **Question:**

> ***Write a program to Find Sum of n Natural Numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>

using namespace std;

int main()
{
    int i,n,sum=0;
    cout<<"\nEnter a number : ";
    cin>>n;

    for(i=1;i<=n;i++)
    {
        sum=sum+i;
    }

    cout<<"\nSum of first [ "<<n<<" ] Numbers : "<<sum<<"\n";
    return 0;
}

```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to Convert Kilometer to Miles.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>

int main() {
	float kilometers;
	std::cout << "Enter Length in Kilometer  : ";
	std::cin >> kilometers;
	float miles = (0.621371* kilometers);
	std::cout << miles << " Miles";
	return 0;
}

```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to Convert Yard to Foot.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>

int main() {
  float yard;
  float foot;
	std::cout << "Enter Length in Yard  : ";
	std::cin >> yard;
	foot = (3*yard);
	std::cout << yard << " Yard in Foot = " << foot;
	return 0;
}


```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to Convert Inch to Cm.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>

int main() {
  float inch;
  float cm;
	std::cout << "Enter Length in inch  : ";
	std::cin >> inch;
	cm = (2.54*inch);
	std::cout << inch << " Inch in cm = " << cm;
	return 0;
}


```
----------------------------------------

# Question 29

### **Question:**

> ***Write a program to Find Sum of Square of first n Natural numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>

using namespace std;

int main()
{
    unsigned long n,i,sum=0,d;
    cout<<"Enter a number : ";
    cin>>n;

    for(i=1;i<=n; i++)
    {
        d=i*i;
        sum = sum + d;
    }

    cout<<"\nSum of square of [ "<<n<<" ] Numbers = "<<sum<<"\n";
    return 0;
}
```
----------------------------------------

# Question 30

### **Question:**

> ***Write a program to Design Simple Calculator.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
# include <iostream>
using namespace std;

int main()
{
    char op;
    float num1, num2;

    cout << "\nEnter a number : ";
    cin >> num1;
    cout << "\nEnter a number : ";
    cin >> num2;

    cout << "\nEnter operator [ + or - or * or / ] : ";
    cin >> op;


    switch(op)
    {
        case '+':
            cout <<"\nAddition of [ "<<num1<<" + "<<num2<<" ] = "<< num1+num2<<"\n";
            break;

        case '-':
            cout <<"\nSubtraction of [ "<<num1<<" - "<<num2<<" ] = "<< num1-num2<<"\n";
            break;

        case '*':
            cout <<"\nMultiplication of [ "<<num1<<" * "<<num2<<" ] = "<< num1*num2<<"\n";
            break;

        case '/':
            cout <<"\nDivision of [ "<<num1<<" / "<<num2<<" ] = "<< num1/num2<<"\n";
            break;

        default:
            cout << "\nError! operator is not correct\n";
            break;
    }

    return 0;
}
```
----------------------------------------


# Question 31

### **Question:**

> ***Write a program to Concatenate Two Strings.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    string s1, s2, result;

    cout << "Enter the first string : ";
    getline (cin, s1);

    cout << "Enter the second string : ";
    getline (cin, s2);

    result = s1 + s2;

    cout << "String obtained on concatenation : "<< result;

    return 0;
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to Find the Number of Digits in a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
    int n,num,i=0;

    cout<<"Enter a number : ";
    cin>>n;

    num=n;

    while(num>0)
    {
        num=num/10;
        i++;
    }
    cout<<"\nNumber of Digits in a number [ "<<n<<" ] is : "<<i<<"\n";

   return 0;
}
```
----------------------------------------


# Question 33

### **Question:**

> ***Write a program to Check Whether a entered character is Vowel or Consonant.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
    char ch;
    cout<<"Enter a Character : ";
    cin>>ch;
    if(ch=='a' || ch=='e' || ch=='i' || ch=='o' || ch=='u')
        cout<< ch<< " is a Vowel";
    else if(ch=='A' || ch=='E' || ch=='I' || ch=='O' || ch=='U')
        cout<< ch<<" is a Vowel";
    else
        cout<< ch<<" is a Consonant";
    cout<<endl;
    return 0;
}
```
----------------------------------------

# Question 34

### **Question:**

> ***Write a program to Convert Celsius to Fahrenheit.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
    float celsius, fahrenheit;
    cout<<"Enter the Temperature in Celsius : ";
    cin>>celsius;
    fahrenheit = (celsius*1.8)+32;
    cout<<"\nEquivalent Temperature in Fahrenheit : "<<fahrenheit;
    cout<<endl;
    return 0;
}

```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program to Convert Pounds to Grams.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
    float pound,gram;
    cout<<"Enter Weight in Pounds  : ";
    cin>>pound;
     gram = pound*453.592;
    cout<<pound<<" Pound  = "<< gram << " Grams ";
    cout<<endl;
    return 0;
}

```
----------------------------------------


# Question 36

### **Question:**

> ***Write a program to Find Quotient and Remainder.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{    
    int divisor, dividend, quotient, remainder;

    cout << "Enter dividend: ";
    cin >> dividend;

    cout << "Enter divisor: ";
    cin >> divisor;

    quotient = dividend / divisor;
    remainder = dividend % divisor;

    cout << "Quotient = " << quotient << endl;
    cout << "Remainder = " << remainder;

    return 0;
}
```
----------------------------------------


# Question 37

### **Question:**

> ***Write a program to calculate discount.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main() {
	int bill;
	int discount;

	cout << "Enter bill amount : ";
	cin >> bill;

	cout << "Enter discount percentage : ";
	cin >> discount;

	int afterDiscount = bill - (bill * discount / 100);

	cout << "After discount your bill is : " << afterDiscount;
	
	return 0;
}
```
----------------------------------------


# Question 38

### **Question:**

> ***Write a program to Swap two numbers using a Temporary variable.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    int a, b, temp;
    
    cout << "\nEnter first number : ";
    cin >> a;
    cout << "\nEnter second number : ";
    cin >> b;

    cout << "\nBefore swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "\nAfter swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    return 0;
}
```
----------------------------------------


# Question 39

### **Question:**

> ***Write a program to Swap two numbers without using a Temporary variable.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
    
    int a, b;
    
    cout << "\nEnter first number : ";
    cin >> a;
    cout << "\nEnter second number : ";
    cin >> b;

    cout << "\nBefore swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    a = a + b;
    b = a - b;
    a = a - b;

    cout << "\nAfter swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    return 0;
}
```
----------------------------------------


# Question 40

### **Question:**

> ***Write a program to Reverse Digits of a Number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>

using namespace std;

int main()
{
    int number, reverse = 0;
    cout<<"Enter a number: ";    
    cin>>number;  
    while(number != 0){
        reverse = (reverse * 10) + number % 10;
        number = number/10;
    }    
    cout<<"Reversed Number: "<<reverse<<endl;   
     
    return 0;
}

```
----------------------------------------


# Question 41

### **Question:**

> ***Write a program to Calculate sum of Digits of Entered Number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
   int n, m, sum = 0;

    cout<<"Enter a number : ";
    cin>>n;

   m = n;

   while (m != 0)
   {
  
      sum = sum + m % 10;
      m = m / 10;
   }

cout<<"\nSum of digits of [ "<<n<<" ] is : "<<sum<<"\n";

   return 0;
}
```
----------------------------------------

# Question 42

### **Question:**

> ***Write a program to Get Input from User.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
    int val;
    cout<<"Enter the Number : ";
    cin>>val;
    cout<<"\nThe Entered number is "<<val;
    cout<<endl;
    return 0;
}
```
----------------------------------------



# Question 43

### **Question:**

> ***Write a program to Store and Display Information Using Structure.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

struct student
{
    char name[50];
    int roll;
    float marks;
};

int main() 
{
    student s;
    cout << "Enter information:," << endl;
    cout << "Enter name: ";
    cin >> s.name;
    cout << "Enter roll number: ";
    cin >> s.roll;
    cout << "Enter marks: ";
    cin >> s.marks;

    cout << "\nEntered Information:," << endl;
    cout << "Name: " << s.name << endl;
    cout << "Roll: " << s.roll << endl;
    cout << "Marks: " << s.marks << endl;
    return 0;
}

```
----------------------------------------


# Question 44

### **Question:**

> ***Write a program to get sum of all odd numbers in given range.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main(){

  int i;
  int min,max;
  long sum =0;

  cout << "Enter the minimum range: ";
  cin >> min;

  cout << "Enter the maximum range: ";
  cin >> max;

  for(i = min; i <= max; i++)
    if(i % 2 !=0)
      sum = sum + i;

  cout << "Sum of odd numbers in given range is: " << sum;

  return 0;

}

```
----------------------------------------


# Question 45

### **Question:**

> ***Write a program to generate random numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
#include <cstdlib>
using namespace std;

int main ()
{
  int n, b, i;

  cout << "Enter the number of random numbers you want:" << endl;
  cin >> n;

  cout << "Random numbers are:" << endl;

  for (i = 1; i <= n; i++)
  {
    b = random();
    cout << b << endl;
  }

  return 0;
}
```
----------------------------------------


# Question 46

### **Question:**

> ***Write a program to Display day of week using switch case.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
 
using namespace std;
 
int main()
{
    int day;
 
   cout<<"Enter week number(1-7): ";
   cin>>day;
 
    switch(day)
    {
        case 1: cout<<"Monday";
            break;
        case 2: cout<<"Tuesday";
            break;
        case 3: cout<<"Wednesday";
            break;
        case 4: cout<<"Thursday";
            break;
        case 5: cout<<"Friday";
            break;
        case 6: cout<<"Saturday";
            break;
        case 7: cout<<"Sunday";
            break;
        default: cout<<"Invalid input! Please enter week number between 1-7.";
    }
 
    return 0;
 
}
```
----------------------------------------



# Question 47

### **Question:**

> ***Write a program To print "hello world" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i;
for (i =1; i<=10; i ++)
cout<<"\n hello world";
return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to find square of a number using functions.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int square();
int main()
{
int answer;
answer = square();
cout<<"Square of the given number = "<< answer;
return 0;
}
int square()
{
int x;
cout<<"Enter any integer:";
cin>>x;
return x*x;
}
```
----------------------------------------


# Question 49

### **Question:**

> ***Write a program to Print Number of Days in a Month.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;

int main()
{
    int month;
    cout << "Enter month number (1-12): ";
    cin >> month;

    if(month == 1)
    {
        cout << "Entered month : January " <<endl;
        cout << "Number of days : 31 days" <<endl;
    }
    else if(month == 2)
    {
        cout << "Entered month : February " <<endl;
        cout << "Number of days :  28 or 29 days" <<endl;
    }
    else if(month == 3)
    {
        cout << "Entered month : March " <<endl;
        cout << "Number of days :  31 days" <<endl;
    }
    else if(month == 4)
    {
        cout << "Entered month : April " <<endl;
        cout << "Number of days :  30 days" <<endl;
    }
    else if(month == 5)
    {
        cout << "Entered month : May " <<endl;
        cout << "Number of days :  31 days" <<endl;
    }
    else if(month == 6)
    {
        cout << "Entered month : June " <<endl;
        cout << "Number of days :  30 days" <<endl;
    }
    else if(month == 7)
    {
        cout << "Entered month : July " <<endl;
        cout << "Number of days :  31 days" <<endl;
    }
    else if(month == 8)
    {
        cout << "Entered month : August " <<endl;
        cout << "Number of days :  31 days" <<endl;
    }
    else if(month == 9)
    {
        cout << "Entered month : September " <<endl;
        cout << "Number of days :  30 days" <<endl;
    }
    else if(month == 10)
    {
        cout << "Entered month : October " <<endl;
        cout << "Number of days :  31 days" <<endl;

    }
    else if(month == 11)
    {
        cout << "Entered month : November " <<endl;
        cout << "Number of days :  30 days" <<endl;
    }
    else if(month == 12)
    {
        cout << "Entered month : December " <<endl;
        cout << "Number of days :  31 days" <<endl;
    }
    else
    {
        cout << "Invalid input! Please enter month number between (1-12).";
    }

    return 0;

}
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i;
char name [8] = {'E' , 'I', 'N', 'S', 'T', 'E', 'I', 'N'};
for(i=0; i<8; i++)
cout<<"Element ["<< i <<" ] = "<< name[i] << endl;
return 0;
}
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i, avg, sum = 0;
int num [5] = {16, 18, 20, 25, 36};
for(i=0; i<5; i++)
sum = sum + num [i];
avg = sum/5;
cout<<"Sum of the Elements in the array = "<< sum <<endl;
cout<<"Average of the elements in the array= "<< avg<<endl;
return 0;
}
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to find the greatest of two numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int x, y, *p, *q;
cout<<"Enter any integer:";
cin>> x;
cout<<"Enter any integer:";
cin>> y;
p = &x;
q = &y;
if(*p>*q)
{
cout<<"x is greater than y";
}
else
{
cout<<"y is greater than x";
}
return 0;
}
```
----------------------------------------



# Question 53

### **Question:**

> ***Write a program to check whether the entered number is a prime number or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>

using namespace std;

int main(){

 int num, i, count=0;
    cout << "Enter a Number : ";  
     cin >> num;
    for(i=2; i<num; i++)
    {
        if(num%i == 0)
        {
            count++;
            break;
        }
    }
    if(count==0) {
	
	 cout<< num <<" is a prime number";
    }
    else {
        cout<< num <<" is not a prime number";
    }
        
    return 0;
}
```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i, product = 1;
for( i=1; i<=10; i++)
product = product * i;
cout<<"The product of the first 10 digits = " << product;
return 0;
}
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char a = 'A';
while (a<='Z')
{
cout<<" \n"<< a++;
}
return 0;
}
```
----------------------------------------

# Question 56

### **Question:**

> ***Write a program to Compare Two Strings.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<string.h>
using namespace std;
int main ()
{
    char a[50], b[50];
    cout<<"Enter string 1 : ";
    cin>>a;
    cout<<"Enter string 2 : ";
    cin>>b;
    if(strcmp(a, b)==0)
        cout << "Strings are equal!";
    else
        cout << "Strings are not equal.";
    return 0;
}
```
----------------------------------------

# Question 57

### **Question:**

> ***Write a program to Convert Lowercase to Uppercase.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;

int main()
{
   char ch;
   cout<<"Enter a character in lowercase: "; 
   cin>>ch;
   ch=ch-32;
   cout<<"Entered character in uppercase: "<<ch;
   return 0;
}
```
----------------------------------------

# Question 58

### **Question:**

> ***Write a program to check whether the entered character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char ch = 'a';
if(islower(ch))
cout<<"you have entered the lower case letter";
else
cout<<"you have entered the upper case letter";
return 0;
}
```
----------------------------------------
