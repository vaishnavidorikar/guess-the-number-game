
package numberguessgame;

import java.util.Scanner;
import java.util.Random;
public class NUMBERGUESSGAME {

   
    public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
       Random random=new Random();
       int RandomNumber=random.nextInt(100) + 1;
       boolean  play=true;
       int attempt=5;
       int score=0;
       while(play)
       {
        
        for(int i=0;i < attempt;i++)
        {
            System.out.println("Enter your number");
            int Num=sc.nextInt();
            if ( Num < RandomNumber )
            {
                System.out.println("Your guess is too low");
            }
            else if ( Num > RandomNumber )
            {
                System.out.println("Your guess is too high");
            }
            else if ( Num == RandomNumber )
            {
                System.out.println("Congratulations your guess is correct");
            }
            
        }
        System.out.println("Your attempts got over");
        System.out.println("Do you want to exit press 1");
        int choice=sc.nextInt();
        if(choice==1)
        {
            play=false;
        }
        
       }
       System.out.println("your score is" + score);
    
}
}
