
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

