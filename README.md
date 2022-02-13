// Java-University-Lab2

import java.util.Arrays;

public class ClassA {
	private final int SIZE_ARRAY = 5;
	public int numItems;
	public int[] arrItems;

	public ClassA(int n, int[] arr) {
		numItems = n;
		arrItems = arr;
	}

	public ClassA() {
		numItems = 0;
		arrItems = new int[SIZE_ARRAY];
	}
	/*
	 * Add a public method equals
	 */
	public boolean equals (ClassA otherClass) {
//		if (this.numItems == otherClass.numItems)				
//			System.out.println("Yes");
//		else {
//			System.out.println("NO");
//		}
//		if (this.arrItems == null && otherClass.arrItems == null)				
//			System.out.println("Yes");
//		else {
//			System.out.println("NO");
//		}
//		
//		if (Arrays.equals(this.arrItems, otherClass.arrItems))				
//			System.out.println("Yes");
//		else {
//			System.out.println("NO");
//		}
		
		if (this.numItems == otherClass.numItems && ((this.arrItems == null && otherClass.arrItems == null) || (Arrays.equals(this.arrItems, otherClass.arrItems))))
		{
			return true;
		} else {
			return false;
		}
	}
}
