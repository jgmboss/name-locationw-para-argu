import java.util.Scanner;

public class parameterAndArguementsNameNlocation
{ public static void greetings(String name, String location){
        System.out.println ("Hello " + name + " of " + location);

    }

    public static void main (String [] arg) {
        Scanner input = new Scanner (System.in);
        System.out.println ("Hey what's your name?");
        String name = input.nextLine();

        System.out.println ("Okay, " + name + " Where do you come from?");
        String location = input.nextLine();
        greetings(name, location);
    }
}
