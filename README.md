# zooforhomework
public class zoo{
         public static void main(String[] args){
                  
         }
}
//SprWu:
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
	class Cat extends Animal{
		String name = "Small Cat";
		int age = 2;
		Cat(){};
		Cat(String name,int age){
			this.name = name;
			this.age = age;
		}
	}
// aldeliki ：
