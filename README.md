import java.io.*;
public class Main
{
public void methodOne()
{
System.out.println("no arguement");
}
public void methodOne(int x,int y)
{
System.out.println(x+y);
}
public void methodOne(int d)
{
System.out.println(d);
}
public void methodOne(double d)
{
System.out.println(d);
}
public static void main(String args[])
{
Main mo=new Main();
mo.methodOne();
mo.methodOne(10);
mo.methodOne(10,20);
mo.methodOne(3.14);
}
}
