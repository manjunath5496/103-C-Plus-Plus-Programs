
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
