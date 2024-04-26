# Employee_Info
import java.io.*;
import java.util.*;
 class  Demo
{
    private int id;
    private String name;
    private String city;
    private double salary;

    public void setId(int id)
    {
        this.id=id;
    }
    public int getId()
    {
        return id;
    }
    public void setName(String name)
    {
        this.name=name;
    }
    public String getName()
    {
        return name;
    }
    public void setCity(String city)
    {
        this.city=city;
    }
    public String getCity()
    {
        return city;
    }
    public void setSalary(double salary)
    {
        this.salary=salary;
    }
    public double getSalary() {
        return salary;
    }
}
public class CWH_4
{
    public static void main(String[] args)
    {
        Demo ob= new Demo();

        ob.setId(102);
        ob.setName("kunal patil");
        ob.setCity("Dhule");
        ob.setSalary(60000);
        System.out.println("Employee ID is : " +ob.getId());
        System.out.println("Employee name is : "  +ob.getName());
        System.out.println("Employee city is : " +ob.getCity());
        System.out.println("Employee salary is : " +ob.getSalary());
    }

}
