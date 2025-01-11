# class-and-objects-instance
package Car;
import java.util.Scanner;
class Car{
String model;
int year;
public void inputDetails(){
Scanner sc = new Scanner(System.in);
System.out.print(&quot;Enter the Car Model: &quot;);
model = sc.nextLine();
System.out.print(&quot;Enter the Year of Purchasing: &quot;);
year = sc.nextInt();

}
public void displayDetails(){
System.out.println(&quot;Car Model: &quot; + model);
System.out.println(&quot;Purchased Year: &quot; + year);
}
}
public class objectandinstance {
public static void main(String[]args){
Car mycar = new Car();
mycar.inputDetails();
mycar.displayDetails();
}
}
OUTPUT:
Enter the Car Model: Alto 800
Enter the Year of Purchasing: 2022
Car Model: Alto 800
Purchased Year: 2022
