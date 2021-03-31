# Java-programs
//Discount
import java.util.Scanner;
public class Discount {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the Quantity");
		int x = sc.nextInt();
		if((x*100)>1000)
		{
			System.out.println("you get a dicount of "+(.1*x*100)+ "and your total cost is "+(x*100-(.1*x*100)));
			
		}
		else {
			System.out.print("No discount");
		}

	}

}
