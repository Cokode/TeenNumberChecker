# TeenNumberChecker
This program takes three parameters  of int types and check if any of values is equal to or greater than 13 and also if equal to or lesser than 19 and returns true if it meets the condition

public class TeenNumberChecker {

    public static boolean hasTeen( int num1, int num2, int num3) {

        return num1 >= 13 && num1 <= 19 || num2 >= 13 && num2 <= 19 || num3 >= 13 && num3 <= 19;
    }

    public static boolean isTeen(int sum4) { // this is a second method
        return sum4 >= 13 && sum4 <= 19;
    }

    public static void main(String[] args) {
        System.out.println("The result of this exercise is: " + hasTeen(12, 14, 4));
        System.out.println("While result for this is:  " + isTeen( 12));
    }
}
