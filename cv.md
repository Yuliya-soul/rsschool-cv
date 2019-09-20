# RESUME
 **Yuliya Simonchyk**

 **Contact info:**

  * :email: *<darki@tut.by>*,
  * :telephone_receiver: +375296731288

 **Summary**:My goal is to get and enrich knowledge of Front-end web development . Adapt my knowledge to real life project to get a work in this field. 
 >“I am such a person that if you ask me a question for which I do not know the answer, I will answer that I do not know. But, believe me, I know how to find it, this answer, and I will find it. Isn't that the main thing?”
 *The Pursuit of Happiness* (https://www.adme.ru/tvorchestvo-kino/15-vdohnovlyayuschih-citat-iz-filma-v-pogone-za-schastem-1045160/)

 **Skills**: basic knowledge in Pascal and Java programming, also also started training in front-end programming.

 **Code examples**:
```javascript
//Flower sort inheritance//
package  flowerGirl;
public  class  Rose  extends  Flower{
public  Rose(int  price,String  nameOfFlower,Colour  color, Freshness  fresh,
int  lengthOfStalk) {
super(price, nameOfFlower, color, fresh, lengthOfStalk);
}
@Override
public  String  getNameOfFlower(){
return  this.nameOfFlower="Rose";
}
public  int  Cost1(){
int  cost=0;
switch (this.freshness) {
case  FullFresh:
break;
case  MiddleFresh:
cost=cost-1;
break;
case  OldFresh:
cost=cost-2;
break;
default:
System.out.println(" Check the freshness of the rose. It is not set.");
break;}
return  cost;
}
public  void  show() {
System.out.printf("%6s %10s %18s %6s %6s ",getNameOfFlower(),getColour(),
getFreshness(), getPrice(),getLengthOfStalk());
}}
 }
 //Lucky numbers//
import  java.util.ArrayList;
import  java.util.Scanner;
import  java.util.Iterator;
public  class  LuckyNumbers {
public  static  void  main(String[] args) {
ArrayList<Integer> list1 = new  ArrayList<Integer>();
ArrayList<Integer> list2 = new  ArrayList<Integer>();
ArrayList<Integer> list3 = new  ArrayList<Integer>();
int  n=100;
int  len=n;
int  i1=0;
int[] counters = new  int [len];
for (int  i =1; i < n; i++)
{ for (int  j=1;j<=n;j++){
int  b = i;
int  a=j;
int  d=gcd_1(a,b);
a=d;
if (((d==1))||(d==n)){
}
else {
list1.add(i);
break;}
}
}
list1.add(0, 1);
System.out.println("Простые числа");
System.out.print(" "+ list1);
int  retval = list1.size();
int  i2=1;
while (i2< (retval-1)){
i2=i2+2;
list2.add(i2);
}
list2.add(0, 1);
System.out.println("");
System.out.println("Prime numbers without even numbers");
list1=list2;
System.out.print(" "+ list1);
int  sb = list1.size();
System.out.println("");
System.out.println("Prime numbers without even numbers and every 3rd number");
for (int  i3 = 2; i3 < sb; i3 += 2)
{
list1.remove(i3);
sb = list1.size();
}
System.out.print(" "+ list2);
list3=list1;
int  sb1 = list3.size();
System.out.println("");
System.out.println("Prime numbers without even numbers and every 3rd number and 7th number");
for (int  i4 = 6; i4 < sb1; i4 += 6)
{
list3.remove(i4);
sb1 = list3.size();
} System.out.print(" "+ list3);
}
public  static  int  gcd_1(int  a, int  b)
{
while (a != b) {
if (Math.abs(a) > Math.abs(b)) {
a =Math.abs(a) - Math.abs(b);
} else {
b = Math.abs(b) - Math.abs(a);
}
}
return  a;
}
}

```

 **Experience**:programming Pascal and Java as part of a course study

 **Education**:

- c ++ programming course 

- basic Pascal at school

- Java book self-study


 **English**: studied English at a English specialized school, then at courses International house level upper- intermediate and received a certificate *FCE*[https://www.ih.by/mezhdunarodnye-ekzameny/cambridge/fce/]

