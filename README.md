```java
package Model;

public class Me {
  private String name;
  private int age;
  private String from;
 
  public Me(String name, int age, String from) {
    this.name = name;
    this.age = age;
    this.from = from;
  }
  
  public void study() {
    System.out.println(
      "Java - Spring Boot" +
      "\nHTML" +
      "\nCSS" +
      "\nMySQL"
    );
  }
  
  public void showInfo() {
    System.out.println(
      "Name: " + this.name +
      "\nAge: " + this.age +
      "\nFrom: " + this.from
    );
  }
}

package Main;
import Model.Me;

public class Main {
  public static void main(String[] args) {
    Me me = new Me(
      "Lucas Felipe", 
      28, 
      "Florianópolis, SC - Brazil"
    );
    
    me.showInfo();
    me.study();
  }
}
```
