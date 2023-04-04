```java
package Model;

public class Me {
  private String name;
  private int age;
  private String from;
  
  public Me() {
  } 

  public Me(String name, int age, String from) {
    this.name = name;
    this.age = age;
    this.from = from;
  }
  
  public void setName() {
  }
  public String getName() {
  }
  public void setAge() {
  }
  public int getAge() {
  }
  public void setFrom() {
  }
  public String getFrom() {
  }
  
  public void study() {
    System.out.println("Java - Spring Boot");
    System.out.println("HTML");
    System.out.println("CSS");
    System.out.println("MySQL");
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
    
    me.study();
  }
}
```

