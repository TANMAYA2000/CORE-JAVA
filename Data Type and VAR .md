# Data types in Java
* Byte
* Short
* Int 
* Long
* Float
* Double 
* Char
* Boolean
* String

# VAR
* In version 10 of Java "Var" introduced
* It is dynamic in nature
* It can only be local varibale
* It is not a keyword and it can be used as variable name

```Java
public class A {
	public static void main(String[] args) {
		A t1 = new A();
		t1.test();
	}

	public void test() {
		var var = 10;
		System.out.println(var);

	}
}
```
