
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
    cout << "Area of Rectangle : " << area <<endl;
      
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
    cout << "Area of Parallelogram : " << area <<endl;
      
    return 0;
}
	
```
----------------------------------------
