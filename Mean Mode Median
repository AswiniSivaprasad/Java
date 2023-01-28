import java.util.*;
import java.util.Scanner;
public class mmm
{
public static void main(String[] args)
{
Scanner input=new Scanner(System.in);
System.out.print("Enter Size of array: ");
int n=input.nextInt();
int[] a=new int[20];
System.out.print("Enter elements of array: ");
for(int i=0;i<n;i++)
{
a[i]=input.nextInt();
}
int sum=0;
for(int i=0;i<n;i++)
{
 sum=sum+a[i]; }
int mean=sum/n;
System.out.println("mean: "+mean);
for(int i=0;i<n;i++)
{
 for(int j=i+1;j<n;j++)
 {
 if(a[i]>a[j])
 {
 int temp=a[i];
 a[i]=a[j];
 a[j]=temp;
 }
 } }
for(int i=0;i<n;i++)
{
 if(n%2==0)
 {
 int mid=n/2;
 System.out.print("median: "+a[mid-1]);
 break;
 }
 else
 {
 int mid=(n+1)/2;
 System.out.println("median: "+a[mid-1]);
 break;
 } }
for(int i=0;i<n;i++)
{
 for(int j=i+1;j<n;j++)
 {
 if(a[i]==a[j])
 {
 System.out.println("mode: "+a[i]);
 break;
 }
 } 
}
}
}
