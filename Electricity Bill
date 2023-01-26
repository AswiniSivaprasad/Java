import java.util.Scanner; class ElectBill
{
int ConsumerNo;
String ConsumerName; int PrevReading;
int CurrReading; String EBConn; double Bill;
void input_data()
{
Scanner sc = new Scanner(System.in); System.out.println("\n Enter Consumer Number: "); ConsumerNo = sc.nextInt();
System.out.println("\n Enter Consumer Name: "); ConsumerName = sc.next(); System.out.println("\n Enter Previous Units: "); PrevReading = sc.nextInt();
System.out.println("Enter Current Units consumed:"); CurrReading = sc.nextInt();
System.out.println("Enter the types of EB Connection(domestic or commercial)"); EBConn = sc.next();
}
double calculate_bill()
{
int choice; if(EBConn=="domenstic")
choice=1; else
choice=2; switch(choice)
{
case 1:
if(CurrReading>=0 && CurrReading<=100) Bill=CurrReading*1;
else if(CurrReading>100 && CurrReading <= 200) Bill=(100*1)+((CurrReading-100)*2.50);
else if(CurrReading>200 && CurrReading <= 500) Bill=(100*1)+(100*2.50)+((CurrReading-200)*4);
else
Bill=(100*1)+(100*2.50)+(300*4)+((CurrReading-500)*6);
break; case 2:
if(CurrReading>=0 && CurrReading<=100) Bill=CurrReading*2;
else if(CurrReading>100 && CurrReading <= 200) Bill=(100*1)+((CurrReading-100)*4.50);
else if(CurrReading>200 && CurrReading <= 500) Bill=(100*1)+(100*2.50)+((CurrReading-200)*6);
else
Bill=(100*1)+(100*2.50)+(300*4)+((CurrReading-500)*7);

break;
}
return Bill;
}
void display()
{
System.out.println("	");
System.out.println("ELCTRICITY BILL"); System.out.println("	");
System.out.println("Consumer Number: "+ConsumerNo); System.out.println("Consumer Name: "+ConsumerName); System.out.println("Consumer Previous Units: "+PrevReading); System.out.println("Consumer Current Units: "+CurrReading); System.out.println("Type of EBConnection: "+EBConn); System.out.println("	");
System.out.println("Total Amount(Rs.): "+Bill);
}
}
class electricitybill
{
public static void main (String[] args)
{
ElectBill b=new ElectBill(); b.input_data(); b.calculate_bill(); b.display();
}
}
