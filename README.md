# amu
#include<iostream.h>
#include<conio.h>
#define pi 3.142
inline float circum(float r)
{
	return(2*pi*r);
}
inline float area(float r)
{
	return(pi*r*r);
}
void main()
{
	float r;
	clrscr();
	cout<<"Enter the radius"<<endl;
	cin>>r;
	cout<<"Area of the circle is="<<area(r)<<endl;
	cout<<"Circumference of the circle is="<<circum(r)<<endl;
	getch();
}
