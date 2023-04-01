# Java-Homework
package class03;

import java.util.Scanner;

public class HW4 {
    public static void main(String[] args) {

        Scanner input=new Scanner(System.in);
        System.out.println("GRADE Calculator "+" May you please Enter your score in the Quiz /100");
        double quizSc=input.nextDouble(); // score might be decimal number
        System.out.println("May you please Enter your score in the mid-term /100");
        double mid_termSC=input.nextDouble(); 
        System.out.println("May you please Enter your final score");
        double finalSc=input.nextDouble(); 


        double average = (quizSc+mid_termSC+finalSc)/3;
        if (average>=90){
            System.out.println("Grade A");
        } else if (average>=70 && average<90) {
            System.out.println("Grade B");
        } else if (average>=50 && average<70) {
            System.out.println("Grade C");
        } else if (average<50) {
            System.out.println("Failed");
        }


    }

    }
