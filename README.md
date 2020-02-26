# Characters-in-a-String-Java_interview_practice
Java program to find number of characters in a string
package charsinstring;

/**
 *
 * @author Dinesh Nanda
 */

public class CharsInString {

    public static void main(String[] args) {
        
        String string = "The best of both worlds";
        int count = 0;
        
        for(int i = 0; i < string.length(); i++){
            
            if(string.charAt(i) != ' '){
                count++;
            }
        }
        System.out.println("The number of characters in a given string is: "+ count);
    }
    
}
