# factpoial-             number = sc.nextInt();               if(number%2 ==0){                   evenSum +=number;                } else {                   oddSum +=number;                }               System.out.print("Do you want to continues press 1 for yes or 0 for no ");               choice = sc.nextInt();           }           while (choice ==1);           System.out.println("sum of even number:" +evenSum);           System.out.println("sum of odd number:" +oddSum);       }
import java.awt.*;
import java.util.*;

public class loopquestion {                                        //prince kumar
      public static void main(String args[]){
          Scanner sc = new Scanner(System.in);
          int number;
          int choice;
          int evenSum = 0;
          int oddSum= 0;

          do{
              System.out.print("enter the number");
              number = sc.nextInt();
              if(number%2 ==0){
                  evenSum +=number;

              } else {
                  oddSum +=number;

              }
              System.out.print("Do you want to continues press 1 for yes or 0 for no ");
              choice = sc.nextInt();
          }
          while (choice ==1);
          System.out.println("sum of even number:" +evenSum);
          System.out.println("sum of odd number:" +oddSum);
      }

