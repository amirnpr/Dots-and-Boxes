#include <iostream>
#include<stdio.h>
#include <conio.h>
#include <string.h>
using namespace std;
int main() {char n[11][12];int i,x,y,h,m=0,p=0;
for(i=0;i<12;i++){                                                          // gereftan caracterhaye safheye bazi //
n[i][0]='x';n[i][2]='x';n[i][4]='x';n[i][6]='x';n[i][8]='x';n[i][10]='x';
n[i][1]=' ';n[i][3]=' ';n[i][5]=' ';n[i][7]=' ';n[i][9]=' ';
n[i+1][0]=' ';n[i+1][1]=' ';n[i+1][2]=' ';n[i+1][3]=' ';n[i+1][4]=' ';n[i+1][5]=' ';n[i+1][6]=' ';n[i+1][7]=' ';n[i+1][8]=' ';n[i+1][9]=' ';n[i+1][10]=' ';
i++;}
for(i=0;i<11;i++){                                                         // namyesh caracterhaye safheye bazi //
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}
player1:{
cout<<"------------------------------------------------"<<endl;
cout<<"***player 1***"<<endl;
cout<<"------------------------------------------------"<<endl;
mokhtasat1:{                                                               // vorodihaye bazikon //
cout<<"------------------------------------------------"<<endl;
cout<<"enter 1 0r 0 ( khat ofoghi=1 ) - ( khat amodi=0 )"<<endl;
cout<<"------------------------------------------------"<<endl;
cin>>h;                                                                    // amodi ya ofoghi bodan khat //
if(h==1){
cout<<"------------------------------------------------"<<endl;
cout<<"enter x and y (mokhtasat khat)"<<endl;
cout<<"------------------------------------------------"<<endl;
cin>>x>>y;                                                                 // mokhtasat khat ofoghi //
if(n[2*(x-1)][(2*y)-1]==' '){                                                          // barresi khali bodan mahal caracter //
if((((x==1)||(x==2))||(x==3))||((x==4)||((x==5)||(x==6)))){               // khat ofoghi faghat dar satre zoj bashad va vasat khane nabashad) //
n[2*(x-1)][(2*y)-1]='-';
if((n[2*(x-1)+2][(2*y)-1]=='-')||(n[2*(x-1)-2][(2*y)-1]=='-')){                                     // barresi por bodan do satr balatar ya do satr paintar //
if(((n[2*(x-1)+1][(2*y)]=='|')&&(n[2*(x-1)+1][(2*y)-2]=='|'))||((n[2*(x-1)-1][(2*y)-2]=='|')&&(n[2*(x-1)-1][(2*y)]=='|'))){   // barresi khathaye amodi baraye kamel shodan khane //
     if(((n[2*(x-1)-1][(2*y)-2]=='|')&&(n[2*(x-1)-1][(2*y)]=='|'))&&(n[2*(x-1)-2][(2*y)-1]=='-'))                    // gharar dadan shomare bazikon dar vasat khane por shode //
          n[2*(x-1)-1][(2*y)-1]='1';
     if(((n[2*(x-1)+1][(2*y)-2]=='|')&&(n[2*(x-1)+1][(2*y)]=='|'))&&(n[2*(x-1)+2][(2*y)-1]=='-'))
           n[2*(x-1)+1][(2*y)-1]='1';
m=m+1;
if(m==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player1 points="<<m<<endl;
cout<<"------------------------------------------------"<<endl;
for(i=0;i<11;i++){
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}}
if((n[2*(x-1)+2][(2*y)-1]=='-')&&(n[2*(x-1)-2][(2*y)-1]=='-')){                                      // barresi kamel shodan hamzaman do khane //
if(((n[2*(x-1)+1][(2*y)]=='|')&&(n[2*(x-1)+1][(2*y)-2]=='|'))&&((n[2*(x-1)-1][(2*y)-2]=='|')&&(n[2*(x-1)-1][(2*y)]=='|')))
m=m+1;
if(m==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player1 ponts="<<m<<endl;
cout<<"------------------------------------------------"<<endl;}}
goto player1;}                                                                // nobat dobare be bazikon emtiaz gerefte dade mishavad //                
else 
goto lin1;}
else{
lin1:{for(i=0;i<11;i++){
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}
goto player2;}}}                                                              // dadan nobat be bazikon badi //
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat1;}}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat1;}}	
else
if(h==0){                                                                  // khat amodi //
cout<<"------------------------------------------------"<<endl;
cout<<"enter x and y (mokhtasat khat)"<<endl;
cout<<"------------------------------------------------"<<endl;
cin>>x>>y;
if(n[(2*x)-1][2*(y-1)]==' '){
if((((y==1)||(y==2))||(y==3))||((y==4)||((y==5)||(y==6)))){              // khat amodi faghat dar soton zoj bashad va vasat khane nabashad) //
n[(2*x)-1][2*(y-1)]='|';
if((n[(2*x)-1][2*(y-1)+2]=='|')||(n[(2*x)-1][2*(y-1)-2]=='|')){                                    // barresi por bodan do soton jolotar ya do soton aghabtar //
if(((n[(2*x)-2][2*(y-1)+1]=='-')&&(n[(2*x)][2*(y-1)+1]=='-'))||((n[(2*x)][2*(y-1)-1]=='-')&&(n[(2*x)-2][2*(y-1)-1]=='-'))){  // barresi khathaye ofoghi baraye kamel shodan khane //
	if(((n[(2*x)-2][2*(y-1)-1]=='-')&&(n[(2*x)][2*(y-1)-1]=='-'))&&(n[(2*x)-1][2*(y-1)-2]=='|'))
          n[(2*x)-1][2*(y-1)-1]='1';
     if(((n[(2*x)-2][2*(y-1)+1]=='-')&&(n[(2*x)][2*(y-1)+1]=='-'))&&(n[(2*x)-1][2*(y-1)+2]=='|'))
           n[(2*x)-1][2*(y-1)+1]='1';
m=m+1;
if(m==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player1 points="<<m<<endl;
cout<<"------------------------------------------------"<<endl;
for(i=0;i<11;i++){
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}}
if((n[(2*x)-1][2*(y-1)-2]=='|')&&(n[(2*x)-1][2*(y-1)+2]=='|')){                                  // barresi kamel shodan hamzaman do khane //
if(((n[(2*x)-2][2*(y-1)-1]=='-')&&(n[(2*x)][2*(y-1)-1]=='-'))&&((n[(2*x)-2][2*(y-1)+1]=='-')&&(n[(2*x)][2*(y-1)+1]=='-')))
m=m+1;
if(m==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player1 points="<<m<<endl;
cout<<"------------------------------------------------"<<endl;}}
goto player1;}
else 
goto lin1;}
else
goto lin1;}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat1;}}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat1;}}
else
{cout<<"------------------------------------------------"<<endl;
cout<<"error (adad vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat1;}}}

player2:{                                                                                 // *****bazikon dovom***** //
cout<<"------------------------------------------------"<<endl;
cout<<"***player2***"<<endl;
cout<<"------------------------------------------------"<<endl;
mokhtasat2:{
cout<<"------------------------------------------------"<<endl;             
cout<<"enter 1 0r 0 ( khat ofoghi=1 ) - ( khat amodi=0 )"<<endl;
cout<<"------------------------------------------------"<<endl;
cin>>h;
if(h==1){
cout<<"------------------------------------------------"<<endl;
cout<<"enter x and y (mokhtasat khat)"<<endl;
cout<<"------------------------------------------------"<<endl;
cin>>x>>y;
if(n[2*(x-1)][(2*y)-1]==' '){
if((((x==1)||(x==2))||(x==3))||((x==4)||((x==5)||(x==6)))){
n[2*(x-1)][(2*y)-1]='-';
if((n[2*(x-1)+2][(2*y)-1]=='-')||(n[2*(x-1)-2][(2*y)-1]=='-')){
if(((n[2*(x-1)+1][(2*y)]=='|')&&(n[2*(x-1)+1][(2*y)-2]=='|'))||((n[2*(x-1)-1][(2*y)-2]=='|')&&(n[2*(x-1)-1][(2*y)]=='|'))){
	if(((n[2*(x-1)-1][(2*y)-2]=='|')&&(n[2*(x-1)-1][(2*y)]=='|'))&&(n[2*(x-1)-2][(2*y)-1]=='-'))
          n[2*(x-1)-1][(2*y)-1]='2';
     if(((n[2*(x-1)+1][(2*y)-2]=='|')&&(n[2*(x-1)+1][(2*y)]=='|'))&&(n[2*(x-1)+2][(2*y)-1]=='-'))
           n[2*(x-1)+1][(2*y)-1]='2';
p=p+1;
if(p==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player2 points="<<p<<endl;
cout<<"------------------------------------------------"<<endl;
for(i=0;i<11;i++){
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}}
if((n[2*(x-1)+2][(2*y)-1]=='-')&&(n[2*(x-1)-2][(2*y)-1]=='-')){
if(((n[2*(x-1)+1][(2*y)]=='|')&&(n[2*(x-1)+1][(2*y)-2]=='|'))&&((n[2*(x-1)-1][(2*y)-2]=='|')&&(n[2*(x-1)-1][(2*y)]=='|')))
p=p+1;
if(p==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player2 points="<<p<<endl;
cout<<"------------------------------------------------"<<endl;}}
goto player2;}
else 
goto lin2;}
else{
lin2:{for(i=0;i<11;i++){
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}
goto player1;}}}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat2;}}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat2;}}
else
if(h==0){                                                                         // khat amodi //
cout<<"------------------------------------------------"<<endl;
cout<<"enter x and y (mokhtasat khat)"<<endl;
cout<<"------------------------------------------------"<<endl;
cin>>x>>y;
if(n[(2*x)-1][2*(y-1)]==' '){
if((((y==1)||(y==2))||(y==3))||((y==4)||((y==5)||(y==6)))){
n[(2*x)-1][2*(y-1)]='|';
if((n[(2*x)-1][2*(y-1)+2]=='|')||(n[(2*x)-1][2*(y-1)-2]=='|')){
if(((n[(2*x)-2][2*(y-1)+1]=='-')&&(n[(2*x)][2*(y-1)+1]=='-'))||((n[(2*x)][2*(y-1)-1]=='-')&&(n[(2*x)-2][2*(y-1)-1]=='-'))){
	if(((n[(2*x)-2][2*(y-1)-1]=='-')&&(n[(2*x)][2*(y-1)-1]=='-'))&&(n[(2*x)-1][2*(y-1)-2]=='|'))
          n[(2*x)-1][2*(y-1)-1]='2';
     if(((n[(2*x)-2][2*(y-1)+1]=='-')&&(n[(2*x)][2*(y-1)+1]=='-'))&&(n[(2*x)-1][2*(y-1)+2]=='|'))
           n[(2*x)-1][2*(y-1)+1]='2';
p=p+1;
if(p==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player2 points="<<p<<endl;
cout<<"------------------------------------------------"<<endl;
for(i=0;i<11;i++){
cout<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}}
if((n[(2*x)-1][2*(y-1)-2]=='|')&&(n[(2*x)-1][2*(y-1)+2]=='|')){
if(((n[(2*x)-2][2*(y-1)-1]=='-')&&(n[(2*x)][2*(y-1)-1]=='-'))&&((n[(2*x)-2][2*(y-1)+1]=='-')&&(n[(2*x)][2*(y-1)+1]=='-')))
p=p+1;
if(p==13)
goto end;
else{
cout<<"------------------------------------------------"<<endl;
cout<<"player2 points="<<p<<endl;
cout<<"------------------------------------------------"<<endl;}}
goto player2;}
else 
goto lin2;}
else
goto lin2;}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat2;}}
else{
cout<<"------------------------------------------------"<<endl;
cout<<"error (mokhtasat vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat2;}}
else{cout<<"------------------------------------------------"<<endl;
cout<<"error (adad vared shode sahih nist)"<<endl;
cout<<"------------------------------------------------"<<endl;
goto mokhtasat2;}}}
end:{cout<<'\t'<<'\t'<<'\t'<<'\t'<<"------------------------------------------------"<<endl;
for(i=0;i<11;i++){
cout<<'\t'<<'\t'<<'\t'<<'\t'<<'\t'<<'\t'<<n[i][0]<<n[i][1]<<n[i][2]<<n[i][3]<<n[i][4]<<n[i][5]<<n[i][6]<<n[i][7]<<n[i][8]<<n[i][9]<<n[i][10]<<endl;}                                                                  
cout<<'\t'<<'\t'<<'\t'<<'\t'<<"------------------------------------------------"<<endl;
cout<<'\t'<<'\t'<<'\t'<<'\t'<<"player1 points="<<m<<"              "<<"player2 points="<<p<<endl;
cout<<'\t'<<'\t'<<'\t'<<'\t'<<"------------------------------------------------"<<endl;
if(m>p){
cout<<'\t'<<'\t'<<'\t'<<'\t'<<'\t'<<'\t'<<"player1 wins"<<endl;
cout<<'\t'<<'\t'<<'\t'<<'\t'<<"------------------------------------------------"<<endl;}
else{
cout<<'\t'<<'\t'<<'\t'<<'\t'<<'\t'<<'\t'<<"player2 wins"<<endl;
cout<<'\t'<<'\t'<<'\t'<<'\t'<<"------------------------------------------------"<<endl;}}
getch();
}
