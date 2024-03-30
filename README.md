using System;
class Vid
{
    public static void Main(String[] args)
    {
        Console.WriteLine();
        Console.WriteLine();
        Console.WriteLine("                                             VOTER REGISTRATION");
        Console.WriteLine();
        Console.WriteLine("────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────");
        Console.WriteLine("                                 WELCOME TO VOTER'S COMMISSION OFFICE");
        Console.WriteLine();
        Console.WriteLine("Are you a here to regiser");
        Console.WriteLine("1─>Yes");
        Console.WriteLine("2─>No");
        int a =Convert.ToInt32(Console.ReadLine());
        Console.WriteLine();
        if (a == 1)
        {
            Console.WriteLine("                                         Welcome to registration portal");
            Console.WriteLine("─────────────────────────────────────────────────────────────────────────────────────────────────────────────");
            Console.Write("Name     :");
            string name=Console.ReadLine();
            Console.Write("Age      :");
            int age=Convert.ToInt32(Console.ReadLine());
            if (age >= 18 && age<=100)
            {
                Console.Write("Mother name :");
                string m = Console.ReadLine();
                Console.Write("Father name :");
                string f = Console.ReadLine();
                Console.Write("Mobile number :");
                long mno=Convert.ToInt64(Console.ReadLine());
                Console.Write("Mail Id :");
                string mi = Console.ReadLine();
                Console.Write("Address for communication:");
                string ad = Console.ReadLine();
                Console.Write("Pincode :");
                int pi = Convert.ToInt32(Console.ReadLine());
                string id1 = name +age;
                Console.WriteLine("Your Voter id is"+id1);
                Console.WriteLine();
                Console.WriteLine();
                Console.WriteLine("Do you want to Login");
                Console.WriteLine("1─>Yes");
                Console.WriteLine("2─>No");
                a =Convert.ToInt32(Console.ReadLine());
                Console.WriteLine();
                if(a == 1)
                {
                    Console.WriteLine("Enter your Voter id");
                    string id2=Console.ReadLine();
                    Console.WriteLine();
                    if(id2==id1)
                    {
                        Console.WriteLine("Name         :"+name); 
                        Console.WriteLine("Age          :"+age); 
                        Console.WriteLine("Mother name  :"+m); 
                        Console.WriteLine("Father name  :"+f); 
                        Console.WriteLine("Mobile Number:"+mno);
                        Console.WriteLine("Mail Id      :"+mi);
                        Console.WriteLine("Address      :"+ad);
                        Console.WriteLine("Pincode      :"+pi);
                        Console.WriteLine();
                        Console.WriteLine("Your voter id"+id1);
                        Console.WriteLine("Would you like to use your vote");
                        Console.WriteLine("1─>Yes");
                        Console.WriteLine("2─>No");
                        a=Convert.ToInt32(Console.ReadLine());
                        if(a == 1)
                        {
                            Console.WriteLine("These are the parties in Election");
                            Console.WriteLine("1─>YCP");
                            Console.WriteLine("2─>TDP");
                            Console.WriteLine("3─>TLC");
                            Console.WriteLine("Which party would you like to Vote");
                            a = Convert.ToInt32(Console.ReadLine());
                            if(a == 1)
                            {
                                Console.WriteLine("You voted YCP");
                            }
                            else if(a==2)
                            {
                                Console.WriteLine("You voted TDP");
                            }
                            else if(a==3)
                            {
                                Console.WriteLine("You voted TDP");
                            }
                            Console.WriteLine("                                 Thank You for voting");
                        }
                        else
                        {
                            Console.WriteLine("Thank you for registering");
                        }

                    }
                    else
                    {
                        Console.WriteLine("Entered voter id incorrect");
                    }
                }
                else
                {
                    Console.WriteLine("                       Thank you for registering");
                    Console.WriteLine("                             Have a nice day");
                }
                Console.WriteLine();

            }
            else
            {
                Console.WriteLine("Sorry you are Minor");
                Console.WriteLine("Please visit us after "+(18-age)+" Later");
            }
        }
        else
        {
            String name="jagadeesh", m="raji", f="Subbarao", mi="gopujagadeesh485@gmail.com", ad="fxjchsak",id1;
            id1 = "jaga123";
            long age=20, mno=8688173593, pi=522001;

            Console.WriteLine("Do you want to login :");
            Console.WriteLine("1─>Yes");
            Console.WriteLine("2─>No");
            a = Convert.ToInt32(Console.ReadLine());
            if(a == 1)
            {
                Console.WriteLine("Enter your Voter id");
                string id2 = Console.ReadLine();
                Console.WriteLine();
                if (id2 == id1)
                {
                    Console.WriteLine("Name         :" + name);
                    Console.WriteLine("Age          :" + age);
                    Console.WriteLine("Mother name  :" + m);
                    Console.WriteLine("Father name  :" + f);
                    Console.WriteLine("Mobile Number:" + mno);
                    Console.WriteLine("Mail Id      :" + mi);
                    Console.WriteLine("Address      :" + ad);
                    Console.WriteLine("Pincode      :" + pi);
                    Console.WriteLine();
                    Console.WriteLine("Your voter id" + id1);
                    Console.WriteLine("Would you like to use your vote");
                    Console.WriteLine("1─>Yes");
                    Console.WriteLine("2─>No");
                    a = Convert.ToInt32(Console.ReadLine());
                    if (a == 1)
                    {
                        Console.WriteLine("These are the parties in Election");
                        Console.WriteLine("1─>YCP");
                        Console.WriteLine("2─>TDP");
                        Console.WriteLine("3─>TLC");
                        Console.WriteLine("Which party would you like to Vote");
                        a = Convert.ToInt32(Console.ReadLine());
                        if (a == 1)
                        {
                            Console.WriteLine("You voted YCP");
                        }
                        else if (a == 2)
                        {
                            Console.WriteLine("You voted TDP");
                        }
                        else if (a == 3)
                        {
                            Console.WriteLine("You voted TDP");
                        }
                        Console.WriteLine("                                 Thank You for voting");
                    }
                    else
                    {
                        Console.WriteLine("Thank you for registering");
                    }
                }
                else
                {
                    Console.WriteLine("Entered voter id is incorrect");
                }
            }
        }
    }
}
