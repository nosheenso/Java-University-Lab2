// Java-University-Lab2

public class ClassB {

	private static int counter = 0;

	public ClassB() {
		counter = 1;
	}

	public void incCounter() {
		++counter;
	}

	public int getCounter() {
		return counter;
	}

	public static void main(String[] args) {
		int i;
		ClassB c = new ClassB();
		

		i = c.counter;
		c.incCounter();
		System.out.println("i = " + i + " counter = " + c.counter);
	}

}
