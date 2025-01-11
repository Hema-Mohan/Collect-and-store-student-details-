# Collect-and-store-student-details-
import java.util.Scanner;

 class Student1{
    String name;
    int age;
    float m1,m2,m3,m4,m5,total,average;
    public void inputDetails(){

        Scanner sc = new Scanner(System.in);
        System.out.print("Enter Name: ");
        name = sc.nextLine();
        System.out.print("Enter Age: ");
        age = sc.nextInt();
        System.out.print("Enter Tamil Mark: ");
        m1= sc.nextFloat();
        System.out.print("Enter English Mark: ");
        m2 = sc.nextFloat();
        System.out.print("Enter Maths Mark: ");
        m3 = sc.nextFloat();
        System.out.print("Enter Science Mark: ");
        m4 = sc.nextFloat();
        System.out.print("Enter Social Science Mark:");
        m5 = sc.nextFloat();
        total=m1+m2+m3+m4+m5;
        average=total/5;
    }
    public void displayDetails(){

        System.out.println("\n--------STUDENT DETAILS--------");
        System.out.println("Student Name: " + name);
        System.out.println("Student Age: " + age);
        System.out.println("Tamil: " + m1);
        System.out.println("English: " + m2);
        System.out.println("Maths: " + m3);
        System.out.println("Science: " + m4);
        System.out.println("Social Science: " + m5);
        System.out.println("Total marks scored: " + total);
        System.out.println("Average: " + average);
        
    }
}
public class objectandinstance {

    public static void main(String[]args){

        Student1 s1 = new Student1();
        s1.inputDetails();
        s1.displayDetails();
    }
    
}

OUTPUT:

Enter Name: Hema.M
Enter Age: 18
Enter Tamil Mark: 98
Enter English Mark: 96
Enter Maths Mark: 93
Enter Science Mark: 95
Enter Social Science Mark:90

--------STUDENT DETAILS--------
Student Name: Hema.M
Student Age: 18
Tamil: 98.0
English: 96.0
Maths: 93.0
Science: 95.0
Social Science: 90.0
Total marks scored: 472.0
Average: 94.4

