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
    A a1 = new A();//Here new keyword creates and object and value of x is stored in refrence variable in a1
    Sysytem.out.println(a1.x);
  }
}
```
