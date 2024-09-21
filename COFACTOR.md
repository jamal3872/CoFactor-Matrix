 #include <iostream>
using namespace std;
int main() {
 float c11,c12,c13,c21,c22,c23,c31,c32,c33;
 float a11,a12,a13,a21,a22,a23,a31,a32,a33;

cout<<"Enter The Elements of First Row:";
cin>>c11>>c12>>c13;
cout<<"Enter The Elements of Second Row:";
cin>>c21>>c22>>c23;
cout<<"Enter The Elements of Third Row:";
cin>>c31>>c32>>c33;
   
  c12=-c12;
  c21=-c21;
  c23=-c23;
  c32=-c32;
 
  a11=(c22*c33)-(c23*c32);
   cout<<"The Value of c11:"<<a11<<endl;
 
   
  a12=(c21*c33)-(c23*c31);
 cout<<"The Value of c12:"<<a12<<endl;
   
     
 a13=(c21*c32)-(c22*c31);
 cout<<"The Value of c13:"<<a13<<endl;
   
 
 a21=(c12*c33)-(c13*c32);
 cout<<"The Value of c21:"<<a21<<endl;
 
 
 a22=(c11*c33)-(c13*c31);
 cout<<"The Value of c22:"<<a22<<endl;
 

 a23=(c11*c32)-(c12*c31);
 cout<<"The Value of c23:"<<a23<<endl;


 a31=(c12*c23)-(c13*c22);
 cout<<"The Value of c31:"<<a31<<endl;

 
 a32=(c11*c23)-(c13*c21);
 cout<<"The Value of c32:"<<a32<<endl;


  a33=(c11*c22)-(c12*c21);
 cout<<"The Value of c33:"<<a33<<endl;
 

 return 0;
}
