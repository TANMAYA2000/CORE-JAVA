# TYPES OF VARIABLES
- Local Variables
- Non-Static variables
- Static Variables
- Refrence Variables

  # LOCAL VARIABLES
- Local variables are created inside method and should be used in inside method.
- Without initializing local varialble we cannot use that
```java
public class B {
	public static void main(String[] args) {
		B b1 = new B();
		b1.test(); //calling test method
	}

	public void test() {
		int x = 10; // local variable 
		System.out.println(x);
	}
}
```
## Static and Non Static varibale cannot be same 

# REFRENCE VARIABLE
* Refrence variable is used to hold the object address
