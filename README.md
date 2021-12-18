# Circles
#display area, circumference and radius
#include<iostream>
using namespace std;
int main()
{
	double area;    //declaring variable with datatype double
	double circumference;  //declaring variable with datatype double
	double radius;    //declaring variable with datatype double
	cout << "Enter the radius of your own choice: " << endl;
	cin >> radius;
	area = 3.14 * radius * radius;   //formula to calculate area of circle

	cout << "Area of circle = " << area << endl; //display area of circle to console screen

	circumference = 2 * 3.14 * radius;   //formula to calculate circumference of circle

	cout << "Circumference of circle = " << circumference << endl;  //display circumference of circle to console screen
	return 0;

}
