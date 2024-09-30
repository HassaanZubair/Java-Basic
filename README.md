import java.util.Arrays;
import java.util.Scanner;

public  class Main {
    public static void main(String[] args) {
        System.out.println("Welcome To first project");

        /*
            byte = 1 [-128 to 127]
        short = 2
        int  = 4    1,2,3
        Long = 8
        float = 4   3.142
        double = 8
        char = 2   a,b,c,d
        boolean  = 1   true/false
         */

        //primitive Type

        /*
            String name = "Hassaan Zubair";
        int age =30;
        long contactNumber = +923352403895L;
        String fatherName = "Muhammad Zubair";
        Long fatherContactNumber = +923343953246L;
        char specialCharacter= '*';
        boolean ageIsSmallOrLarge = true;

        byte hello = 127;

        System.out.println(hello);

        //Print the values

        System.out.println(name + "\n" + age + "\n" + contactNumber + "\n" + fatherName + "\n" + fatherContactNumber + "\n" + specialCharacter + "\n" + ageIsSmallOrLarge);
    */

        // non primitive types

/*
        String name = new String("Hassaan");
        String friend = new String("Muhammad zubair");
        String thirdFriendName = name + friend;

        System.out.println(name.length() + "\n" + friend.length());
        System.out.println(thirdFriendName);

 */
        /*
        Strings
        charAT
        length
        replace
        substring
         */

        /*

        String namecharat = "Hassaan";
        System.out.println(namecharat.charAt(6));

        String nameLength = "Zubair";
        System.out.println(nameLength.length());

        String nameReplace = "Affan";
        System.out.println(nameReplace.replace('f', 'n'));

        String nameSubString = "Muhammad Hassaan Zubair";
        System.out.println(nameSubString.substring(9,16));

        */

        //Arrays

      /*  int[] marks= new int[3];
        marks[0] = 100;
        marks[1] = 95;
        marks[2] = 90;

        //array length
        //sort
        //2d array

       // System.out.println(marks.length);

        System.out.println(marks[2]);
        Arrays.sort(marks);
        System.out.println(marks[2]);

       */

/*
        int[][]  finalMarks = {{40,50,60}, {70,80,90}};
        System.out.println(finalMarks[1][2]);
*/

//        casting is used for conversion

    /*

        double price = 200.01;
        double afterSalestaxAdd = price+20;

        System.out.println(afterSalestaxAdd);

        int price2 = (int) 200.01;
        int afterSalesTaxAdd2 = price2 +  (int)  20.18;
        System.out.println(afterSalesTaxAdd2);

*/
        //constants final value dont set in future

    /*     int age;
         age= 23;
         age = 24;
         age  = 25;
        System.out.println(age);

        final float PI = 3.14F;
      */

//        Operator
//        arithmetic    (+,-./.*, % modulo)
//        assignment    ( =, unary operator (++var, var++, --var, var--)
//        logical       (&&, ||, !)
//        comparison    (==,!=, <, >, <=, >=)
//        conditional   (if, else)

//        int num = 5;
//
//        System.out.println(++num);
//        System.out.println(num);

        //Maths
        // Functions
        //.max
        //.min
        //random(range from 0.0 to 1)                      Important

/*        System.out.println(Math.max(10,12));
        System.out.println(Math.min(20,15));
        System.out.println((int) (Math.random()* 100));
        */


        //Input
        //age input krni hai  and naam

  /*
      Scanner SC = new Scanner(System.in);
        System.out.println("Input your Name");
        String name = SC.nextLine();
        System.out.println("Input your age");
        int age = SC.nextInt();
        System.out.println("Input your height");
        float height = SC.nextFloat();

        System.out.println(name);
        System.out.println(age);
        System.out.println(height);
   */


//        comparison operators

/*
        int age = 21;

        if (age > 18)
            System.out.println("Apply for license");

        else
            System.out.println("illegal");
 */

        //Logical Operator

        //petrol price 250   diesel price 270    high octane petrol 290  high octane diesel 330 or anything

   /*     Scanner Sc  =  new Scanner(System.in);
        System.out.println("How cash you are?");
        int cash = Sc.nextInt();
        System.out.println(cash);
        
        if (cash<250){
            System.out.println("Enough money");
            System.out.println("need more cash");
        }
        else if (cash>=329){
            System.out.println("you buy High octane diesel or anything else");
        } else if (cash>=289) {
            System.out.println("Yoy buy High octane petrol");
        }
        else if (cash>=269){
            System.out.println("Yoy buy diesel");
        } else if (cash>250) {
            System.out.println("you buy petrol");
        }*/


        //Switch
        // print week days as a case
      /*  int day = 3;
         switch (day)
         {
             case 1:
                 System.out.println("monday");
                 break;
             case  2:
                 System.out.println("Tuesday");
                 break;
             case 3:
                 System.out.println("wednesday");
                 break;
             default:
                 System.out.println("Thursday");
         }
*/
        /*
        Loops
        for
        while
        do while
        */

          /*
          for (int i = 200; i>1; i--){
                System.out.println(i);
            }
*/    /*int i = 200;
        while (i>=1){
            System.out.println(i);
            i= i-1;
        }*/

/*        int i = 200;
        do {
            System.out.println(i);
            i = i - 1;
        } while (i >= 10);
        */

        //exercise

/*        Scanner Sc = new Scanner(System.in);
            int number = 0;
        do {
            System.out.println("Enter your number");
            number = Sc.nextInt();
            System.out.print("Your number is");
            System.out.println(number);
        }
        while (number>0);
        System.out.println("That End");
        */

        //break and continue
/*        int i = 0;
        while (true) {
            if (i == 2) {
                i = i + 1;
                continue;
            }
            System.out.println(i);
            i = i + 1;
            if (i > 5) {
                break;
            }

        } */

        //try-catch in exception handling

    /*    int[] marks= {76,86,97};
        try {
            System.out.println(marks[5]);
        } catch (Exception exception){
            //do somtething after cathcing
        }
        System.out.println("Welcome Hassaan");

        */

/*        //methods
addnum(6,8);
printNames("hassaan");
printNames("Affan");

        }

    public static void printNames(String name){
        System.out.println(name);
    }

    public static  void addnum(int a, int b) {
        int sum = a+b;
        System.out.println(sum);
    }*/

//Mini project

        Scanner Sc = new Scanner(System.in);
        int myNumber =(int) (Math.random()*100);
        int userNumber = 0;
        do {
            System.out.println("Guess my number (1-100)");
            userNumber = Sc.nextInt();
            if (userNumber == myNumber) {
                System.out.println("You won");
                break;
            } else if (userNumber > myNumber) {
                System.out.println("sorry your nuber is to large");
            } else {
                System.out.println("your number is so small");
            }
            }
            while (userNumber >= 0);

        System.out.print("my number was");
        System.out.println(myNumber);
    }
}


