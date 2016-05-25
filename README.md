import java.util.Scanner;
   public class Calculator 
   {
   public static void main(String[] args) {
 Scanner me = new Scanner(System.in);
        int choice = me.nextInt();
        System.out.println();
        if (choice == 1){
            addition();
        }
        else if (choice == 2){
            subtraction();
        }
        else if (choice == 3){
            division();
        }
        else if (choice == 4){
            multiplication();
        }
 System.out.println();
        me.close();
    }
    public static void addition(){
 int a,b;
        Scanner me = new Scanner(System.in);
 a= me.nextInt();
b = me.nextInt();
 me.close();
        System.out.println("Sum is " + (a+b));
    }
 public static void subtraction(){
        int a,b;
        Scanner me= new Scanner(System.in);
 a = me.nextInt();
 b = me.nextInt();
 me.close();
        System.out.println("difference is"+ (a-b));
    }
 public static void division(){
        int a,b;
        Scanner me = new Scanner(System.in);
  a = me.nextInt();
 b = me.nextInt();
       me.close();
        System.out.println("division is" + (a/b));
    }
  public static void multiplication(){
        int a,b;
        Scanner me= new Scanner(System.in);      
       a=me.nextInt();
 b = me.nextInt();
 me.close();
      System.out.println("multiplication is " + (a*b));
    }
}
