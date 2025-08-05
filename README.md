# URL Locator
A simple Java program that takes a url from the user to determine if thier url is correct or incorrect.
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package url.locator;

/**
 *
 * @author TinyikoMakhubele 240764986
 */
import java.util.Scanner;
public class URLLocator {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // input from the user 
        
        Scanner input = new Scanner(System.in);
        String URL;
        
        System.out.print("Enter your URL:");
        URL=input.nextLine();
        
        if (URL.startsWith("www.") && URL.endsWith(".com")){
              System.out.println("YOUR URL IS CORRECT" + URL);
        }else {
              System.out.println("YOUR URL IS INCORRECT" +  URL);
        }
 
    }
   
            
}
