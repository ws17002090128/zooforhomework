# zooforhomework
public class zoo{
         public static void main(String[] args){
                  
         }
}

	abstract class Animal{
		private String name;
		private int age;
		public void setname(String name) {
			this.name = name;
		}
		public String getname() {
			return this.name;
		}

		public void setage(int age) {
			this.age = age;
		}
		public int getage() {
			return this.age;
		}
	}
//SprWU:
	class Cat extends Animal{
    	Cat(){};
    	Cat(String name,int age){
    		this.name = name;
    		this.age = age;
    	}
    }


// whs：
	 class Sheep extends Animal{
	    String name = "Ian";
	    int age = 3;
            Sheep(){};
            Sheep(String name,int age){
		 this.name = name;
		this.age = age;
		 }
	}
//shangluoye：
	 class tiger extends Animal{
	 String name = "Panthera tigris";
	 int age= 25;
	 tiger（string name,int age）{
	    this.name=name;
	    this.age=age;
	    
	 }
	 }
//SpringServer
public void setDog(String dog){
		this.dog = dog;
	}
