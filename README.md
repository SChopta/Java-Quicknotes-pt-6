
// this. refers to the object without having to know what variable is associated with it
//example: My name is Stef if I refer to myself I use "I" the reference I=Stef aka this. refers to 
//generic reference ex: hey you can refer to more than 1 person same as "I" can refer to different people.
class Frog {
	String name;
	int age;
	
	public void setName(String newName) {
		name = newName;
	}
	
	public void setAge(int newAge) {
		age = newAge;
	}
	
	public String getName() {
		return name;
	}
	public int getAge() {
		return age;
	}
}
public class Project6 {

	public static void main(String[] args) {
		
		Frog frog1 = new Frog();
		//frog1.name = "Bertie";
		//frog1.age = 1;
		
		frog1.setName("Bertie");
		frog1.setAge(1);
		System.out.println(frog1.getName());
	}

}
