# Java-Solved-Programs
Starting the the basics the programs I solved during my preparation 
// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
       
        String s="hi hello; hii";
        Scanner scan =new Scanner(s);
        scan.useDelimiter(";");
        while(scan.hasNext())
        {
        System.out.println(scan.next());
        }
        if(scan.hasNext())
        {
            System.out.print("true");
        }
        else{
            System.out.println("false");
        }
        
    }
}
