import java.util.Scanner;

class Main
{

  static void method1()
  {
    int symptoms;
    String test;

    String setBoldText = "\033[0;1m";
    String setPlainText  = "\033[0;0m";

    Scanner symptoms_list = new Scanner(System.in);
    System.out.println(setPlainText + "(1)Fever\n(2)Cough\n(3)Tiredness\n(4)Aches\n(5)Runny Nose\n(6)Sore Throat\n(7)Headache\n(8)Diarrhea\n(9)Vommiting\n(10)Trouble Breathing\n(11)Chest Pain\n(12)Confusion\n(13)Blue Lips or Blue Face\n(14)None of The Above" + setPlainText);
    System.out.print("\n");
    

    while (true)
    {
      System.out.print("\n");
      System.out.print(setPlainText + "Symptom Number: ");
      symptoms = symptoms_list.nextInt();


    if (symptoms == 1 || symptoms == 2 || symptoms == 3 || symptoms == 4 || symptoms == 5)
    {
      System.out.println(setBoldText + "The symptom you are experiencing is considered mild, you are adivsed to self isolate");
      System.out.print("\n");
      System.out.println(setPlainText + "Thank you for using our app, stay safe");
      System.exit(0);
    }

      if (symptoms == 6 || symptoms == 7 || symptoms == 8 || symptoms == 9)
      {
        System.out.println(setBoldText + "The symptom you are experiencing is considered moderate, you are advised to self isolate, or visit a hospital if the symptom persists or gets worse");
        System.out.print("\n");
        System.out.println(setPlainText + "Thank you for using our app, stay safe");
        System.exit(0);
      } 

      if (symptoms == 10 || symptoms == 11 || symptoms == 12 || symptoms == 13)
      {
        System.out.println(setBoldText + "The symptom you are experiencing is considered severe, you are advised to visit a hospital immediately, and avoid conatact with people.");
        System.out.print("\n");
        System.out.println(setPlainText + "Thank you for using our app, stay safe");
        System.exit(0);
      }

      if (symptoms == 14)
      {
        System.out.println(setBoldText + "You do not have any symptoms of the Corona Virus at the moment");
        System.out.print("\n");
        System.out.println(setPlainText + "Thank you for using our app, stay safe");
        System.exit(0);
      }
      if ((symptoms<1) || (symptoms>14))
        System.out.println("ERROR Please enter a valid number\n");

     }

  }

  public static void main(String[] args) 
  {
    String setBoldText = "\033[0;1m";
    String setPlainText  = "\033[0;0m";
    String name;
    int age;

    System.out.println(setBoldText + "Welcome to the Covid-19 Self Check!" + setBoldText);
    System.out.println("\n");

    Scanner first_name = new Scanner(System.in);
    System.out.print(setPlainText + "Enter your first name: " + setPlainText);
    name = first_name.next();

    Scanner age_old  = new Scanner(System.in);
    System.out.print(setPlainText + "Enter your age: " + setPlainText);
    age = age_old.nextInt();

    
      if (age < 16)
      {
         System.out.println("You are too young to use this application, you have to be 16+");
      } 

      else if(age >= 16)
      {
        System.out.println("\n");
        System.out.print(setBoldText + "Hello " + name);
        System.out.println(setBoldText + " Please Choose the most sever symptom you are experiencing from this list: ");
        method1();
      }

  }
}
