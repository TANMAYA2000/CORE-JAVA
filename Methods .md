# METHODS
* It is a block of code which we can use whenever we needed
* It help us to build resuable module
* Void method cannot return any value
Below example is showing not a void method and return a vlaue
```Java
public class A {
	public static void main(String[] args) {
		A a1 = new A();
		a1.test();//calling test method
	}

	public int test() { //HERE this method is not a void method so return a value is compulsory
		return (10);
	}
}

```
