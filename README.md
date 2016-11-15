import java.io.*;
public class num
{
public static void mani(String args[])
{
Scanner data=new Scanner(System.in);
int n=data.nextInt();
if(n%4==0)
System.out.println("leap year");
else
System.out.println("not leap year");
}
}
