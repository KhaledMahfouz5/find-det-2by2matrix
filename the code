#include<iostream>
using namespace std;
int main() {
float a[2][2],main=1.0,sub=1.0,det;
cout<<" Enter Your 2by2 matrix to find it's determinant\n";
for (int i=0;i<2;i++)
{for(int j=0;j<2;j++)
{cin>>a[i][j];
if(i==j)
{main*=a[i][j];}
else if (i+j==1)
{sub*=a[i][j];}
}}
det=main-sub;
cout<<" The determinant Of Your Matrix = "<<det<<endl;
if(det==0)
cout<<" You Cannot Inverse This Matrix"<<endl;
}
