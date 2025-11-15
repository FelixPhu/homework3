//Name: Felix Phu

import java.util.Scanner;

//Correct answers: Right, Door3

public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        System.out.println("You are in a gameshow. There appears to be a crossroad ahead of you; one path leads to $10,000, while the other leads to nothing.");

        // choice 1
        String choice1 = "";
        while (!choice1.equals("Left") && !choice1.equals("Right")) {
            System.out.println("Choose a direction (Left/Right):");
            choice1 = input.nextLine();

            if (!choice1.equals("Left") && !choice1.equals("Right")) {
                System.out.println("type 'Left' or 'Right'.");
            }
        }

        // choice 1 is wrong
        if (choice1.equals("Left")) {
            System.out.println("You chose Left.");
            System.out.println("A loudspeaker plays: 'Wrong choice! You get nothing!'");
        } 
        // choice 1 is right
        else {
            System.out.println("You chose Right.");
            System.out.println("Correct! You win $10,000!");
            System.out.println("Although, you may choose to test your luck again for 1 million dollars.");

            // choice 2 yes or no
            String choice2 = "";
            while (!choice2.equals("Y") && !choice2.equals("N")) {
                System.out.println("Do you wish to proceed? (Y/N):");
                choice2 = input.nextLine();

                if (!choice2.equals("Y") && !choice2.equals("N")) {
                    System.out.println("type 'Y' or 'N'.");
                }
        }
            // choice 2 yes
            if (choice2.equals("Y")) {
                System.out.println("You chose Yes.");
                System.out.println("Very well. You now have to choose one of three doors: Door 1, Door 2, or Door 3. Behind one of these doors is the money. Choose wisely.");

                // choice 3
                String choice3 = "";
                while (!choice3.equals("1") && !choice3.equals("2") && !choice3.equals("3")) {
                    System.out.println("Which door do you choose? (1/2/3):");
                    choice3 = input.nextLine();

                    //choice 3 invalid answer

                    if (!choice3.equals("1") && !choice3.equals("2") && !choice3.equals("3")) {
                        System.out.println("type '1', '2', or '3'.");
                    }
                }

                // Door 1

                if (choice3.equals("1")) {
                    System.out.println("You chose Door 1");
                    System.out.println("A loudspeaker plays: I will close a wrong door for you. Door 2 closes. Will you switch your choice to Door 3?");

                    String switchdoor = "";

                    while (!switchdoor.equals("Y") && !switchdoor.equals("N")) {
                        System.out.println("Switch to Door 3? (Y/N):");
                        switchdoor = input.nextLine();

                        //door 1 switchdoor invalid answer

                        if (!switchdoor.equals("Y") && !switchdoor.equals("N")) {
                            System.out.println("type 'Y' or 'N'.");
                        }
                    }

                    //door1 switchdoor choice

                    if (switchdoor.equals("Y")) {
                        System.out.println("You switched to Door 3.");
                        System.out.println("Congratulations! You win $1,000,000!");
                    } else {
                        System.out.println("You stayed with Door 1");
                        System.out.println("Wrong choice! You get nothing!");
                    }
                } 

                // Door 2

                else if (choice3.equals("2")) {
                    System.out.println("You chose Door 2");
                    System.out.println("A loudspeaker plays: I will close a wrong door for you. Door 1 closes. Will you switch your choice to Door 3?");

                    String switchdoor = "";
                    while (!switchdoor.equals("Y") && !switchdoor.equals("N")) {
                        System.out.println("Switch to Door 3? (Y/N):");
                        switchdoor = input.nextLine();

                        //door 2 switchdoor invalid answer

                        if (!switchdoor.equals("Y") && !switchdoor.equals("N")) {
                            System.out.println("type 'Y' or 'N'.");
                        }
                    }

                    //door2 switchdoor choice

                    if (switchdoor.equals("Y")) {
                        System.out.println("You switched to Door 3.");
                        System.out.println("Congratulations! You win $1,000,000!");
                    } else {
                        System.out.println("You stayed with Door 2");
                        System.out.println("Wrong choice! You get nothing!");
                    }
                } 
                // Door 3
                else if (choice3.equals("3")) {
                    System.out.println("You chose Door 3.");
                    System.out.println("A loudspeaker plays: I will close a wrong door for you. Door 1 closes. Will you switch your choice to Door 2?");
                    String switchdoor = "";

                    //door 3 switchdoor invalid answer

                    while (!switchdoor.equals("Y") && !switchdoor.equals("N")) {
                        System.out.println("Switch to Door 2? (Y/N):");
                        switchdoor = input.nextLine();
                    
                        if (!switchdoor.equals("Y") && !switchdoor.equals("N")) {
                            System.out.println("type 'Y' or 'N'.");
                        
                            //door3 switchdoor choice
                        }
                    }
                            if (switchdoor.equals("Y")) {
                                System.out.println("You switched to Door 2.");
                                System.out.println("Wrong choice, you get nothing!");
                            } else {
                                System.out.println("You stayed with Door 3");
                                System.out.println("Congratulations, You win $1,000,000! (how many tries did this take)" );

                        }
                    
                }
            } 
            // choice 2 no
            else {
                System.out.println("You chose No. You walk away with your $10,000. Congratulations! (try again plz i spent like so long on the part after this)");
            }
        }

        input.close();
    }
}
