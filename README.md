# EKENE-AMADI
Today's class code
import java.util.Arrays;
import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int[] myArray = {1,3,5,9,8};
        int[] anotherArray = new int[10];
        anotherArray[0] = 1;
        anotherArray[1] = 2;

        String[] gender = {"Female", "Male"};

        for (int i = 0; i < anotherArray.length; i++){
            if (anotherArray[i] == 13){
                System.out.println("Found it");
                break;
            }
            System.out.println("Insert item at:" +i);
            anotherArray[i] = input.nextInt();
        }

        for (int i = 0; i < anotherArray.length; i++){
            System.out.println("Item at:" +i+ " is "+ anotherArray[i]);
        }
        int total = 0;
        for(int i = 0; i < anotherArray.length; i++){
            total += myArray[i];
            System.out.println(total);
        }




        }
    }
