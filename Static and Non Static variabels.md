# Non Static 
1. Non Static variabels are created outside method and inside class 
2. Without creating object we can't access non static variable 
3. Non Static variable are also known as **_Insatance varaible_**
4. Eveytime we create an object copy of non static variable get loaded into the object
```java
//EXAMPLE

public class A {
		  int x = 56;//Non-Static
		  public static void main(String [] args){
		    A a1 = new A();//Here new keyword creates and object and value of x is stored in refrence variable in a1 and a2 both
		    A a2 = new A(); 
		    System.out.println(a1.x);
		    System.out.println(a2.x);
		  }
		}
``` 
* Changes will be made in object and it'ill not affect the original object
```java
public class A {
		  int x = 56;//Non-Static
		  public static void main(String [] args){
		    A a1 = new A();
		    a1.x=10; //here we change the value of object a1 
		    A a2 = new A();
		    System.out.println(a1.x);
		    System.out.println(a2.x);//orginally it prints out 56
		  }
		}
```
# Static

1. Static is also known as class **_variable_**
2. Static variable is created outside class inside method using static keyword
3. Static variable belongs to class
4. Do not create object to access static variable
```java
public class Static {
	static int x= 25;//Static (belongs to class), known as class variable
	public static void main(String[] args) {
		System.out.println(Static.x);
	}
}
```
* There is only one copy of static variable that is loaded into class (common memory)
```java
public class Static {
	static int x= 56;//class variable
	public static void main(String[] args) {
		System.out.println(Static.x);
		Static.x=23;
		System.out.println(Static.x);
	}
}
```
