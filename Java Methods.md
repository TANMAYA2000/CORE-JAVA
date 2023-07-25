# JAVA METHODS
* Block of code that we can use whenever we needed
```java
package gitmd_files;


public class A {
           public static void main(String[] args) {//this is main method 
			A a1 = new A();
			a1.test();//call to test method
			}

		public void test() {// this is the second method 
			System.out.println("100");
			
		}
}
```

**If method is Static**
```java
public class A{
	 public static void main(String[] args) {
		 A.test1();
	 }
	 
  public static void test1() {//this is a static method
	  System.out.println("100");
  }
}
```



