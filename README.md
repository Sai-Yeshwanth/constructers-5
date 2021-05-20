Error!!! can't call the constructer twice with same object

class Add
{
	Add()
	{
		System.out.println();
	}

}
class Jala {
	
	public static void main(String[] args) {
		Add a = new Add();
		Add a = new Add(); //error
		
	}
}
