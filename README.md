# ThreeTimes
String exercise
package stringAssignments;

import java.util.Scanner;

public class ThreeTimes {
     public static void main(String[] args) {
		
    	 Scanner nany = new Scanner(System.in);
    	 System.out.println("Enter please any word");
    	 String word =nany.next();
    	 if (word.length()>=2) {
    		 System.out.print(word.charAt(0)+""+word.charAt(1));
    		 System.out.print(word.charAt(0)+""+word.charAt(1));
    		 System.out.print(word.charAt(0)+""+word.charAt(1));
    	 }
    	 nany.close();
	}
}
