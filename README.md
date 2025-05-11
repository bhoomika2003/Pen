# Pen
First example program on OOPs

class Pen{
	String colour;
	String type;
	
	public void write() {
		System.out.println("Write SomeThing!!!");
	}
}
public class OOPs1 {
	
	public static void main(String[] args) {
		Pen p1 = new Pen();
		p1.colour = "Blue";
		p1.type = "Gel";
		
		System.out.println("the color of the pen-" +p1.colour + " And the type of the pen is" +p1.type);
		p1.write();
	}

}
