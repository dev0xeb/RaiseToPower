# RaiseToPowerimport java.util.Scanner;
public class RaiseToPower
{
	public static void main(String[] args)
	{
	Scanner input = new Scanner(System.in);

	double baseNumber;
	double powerNumber;
	double raiseToPower;

	System.out.print("Enter a number: ");
	baseNumber = input.nextInt();

	System.out.print("Enter a number: ");
	powerNumber = input.nextInt();

	raiseToPower = Math.pow(baseNumber, powerNumber);
	System.out.printf("the raise to power is %.0f", raiseToPower);
	}
}
