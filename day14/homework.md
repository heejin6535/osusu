```java
package day14.quiz;

public class Tourist {
	private String name;
	private double budget;
	private static String dtt;
	
	public Tourist(String name) {
		this.name = name;
	}
	
	public Tourist(double budget) {
		this(null, budget);
	}
	
	public Tourist(String name, double budget) {
		setData(name, budget);
	}
	
	public void setData(String name, double budget) {
		setName(name);
		setBudget(budget);
		
	}
	
	public String getName() {
		return name;
	}
	
	public void setName(String name) {
		this.name = name;
	}
	
	public double getBudget() {
		return budget;
	}
	
	public double setBudget(double budget) {
		if()
		
	}


}
```
