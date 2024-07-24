/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package calculatepower;

import java.util.Scanner;
public class CalculatePower {


    public static void main(String[] args) {
        int Base  ;
        int Degree ;
        double sum;
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter you Base : ");
        Base = scanner.nextInt();
        System.out.print("Enter you Degree : ");
        Degree = scanner.nextInt();
        
        sum = Math.pow(Base, Degree);
        
         int Result = (int) sum;
        System.out.print("Base : " + Base );
        System.out.print("\n" );
        System.out.print("Degree : " + Degree );
        System.out.print("\n" );
        System.out.print("Result PowerNumber : " + Result );
        System.out.print("\n" );
    }
    
}
