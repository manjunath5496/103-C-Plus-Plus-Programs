
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
