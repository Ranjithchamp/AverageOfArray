# AverageOfArray
import java.util.Arrays;
import java.util.Scanner;

public class AverageOfArray {

	public static void main(String[] args) {

		Scanner get = new Scanner(System.in);
		System.out.println("Enter array Size");
		int n = get.nextInt();
		int array[] = new int[n];
		System.out.println("enter array values");
		for (int i = 0; i < array.length; i++) {
			array[i] = get.nextInt();
		}

		int sum = 0;
		for (int i = 0; i < array.length; i++) {
			sum = sum + array[i];
		}
		System.out.println("Average of Array =" + sum / array.length);

	}

}
