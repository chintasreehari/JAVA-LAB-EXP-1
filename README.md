# JAVA-LAB-EXP-1
##TITTLE:-DefaultPremitiveValue Program
```java
class  DefaultPremitiveValues
{
byte b;
short s;
int i;
long l;
float f;
double d;
char c;
boolean bool;
public static void main(String[] args){
DefaultPremitiveValues obj= new DefaultPremitiveValues();
System.out.println("default byte value :"+obj.b);
System.out.println("default byte value :"+obj.s);
System.out.println("default byte value :"+obj.i);
System.out.println("default byte value :"+obj.l);
System.out.println("default byte value :"+obj.f);
System.out.println("default byte value :"+obj.d);
System.out.println("default byte value :"+obj.c);
System.out.println("default byte value :"+obj.bool);
}
}

```
#output
![output of Primitive](Primitive.png)



##TITTLE:-QuadraticEquation program
```java
import java.util.Scanner;
class QuadraticEquation
{
public static void main(String[] args)
{
Scanner sc=new Scanner(System.in);
System.out.print("enter coeffici a:");
double a= sc.nextDouble();
System.out.print("enter coeffi b:");
double b=sc.nextDouble();
System.out.print("enter coeffici c:");
double c=sc.nextDouble();
double d=(b*b)-(4*a*c);
System.out.println("discriminant="+d);
if(d>0)
{
double x1=(-b+Math.sqrt(d))/(2*a);
double x2=(-b-Math.sqrt(d))/(2*a);
System.out.println("roots are real and diff");
System.out.println("x=:"+x1);
System.out.println("x=:"+x2);
}
else if(d==0)
{
double x=-b/(2*a);
System.out.println("x=:"+x);
}
else
{
double real=-b/(2*a);
double imaginary=Math.sqrt(-d)/(2*a);
System.out.println("x1="+real+"+i"+imaginary);
System.out.println("x2="+real+"-i"+imaginary);
}
sc.close();
}
 }
```
#output
![output of Quadratic](Quadratic.png)

