```java
package Model;

public class Me {
  private String name;
  private int age;
  private String from;
  private String educationOngoing;
 
  public Me(String name, int age, String from, String educationOngoing) {
    this.name = name;
    this.age = age;
    this.from = from;
    this.educationOngoing = educationOngoing;
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
      "\nFrom: " + this.from +
      "\nEducation (ongoing): " + this.educationOngoing
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
      "Florianópolis, SC - Brazil",
      "Information Systems - UNISUL"
    );
    
    me.showInfo();
    me.study();
  }
}
```
