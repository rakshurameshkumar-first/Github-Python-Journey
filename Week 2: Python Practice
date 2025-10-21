print("Quick Tool Kit: Hosted By Rakshu Technologies!")
print("We have Various Tools, Including Receipt Calculators and Idea Notepads" +
      "That Save and Generate on Command!")
Tool = input("What Tool Would You Want To Use? Note Invalid Answers Direct You To Receipt Calculators")

if (Tool == "Idea Notepad"):
    print("Welcome To Your Idea Notepad, Hosted by Rakshu Technologies")
    IdeaRight = input("To begin, type 'Hello!'")
    if IdeaRight.lower() == "hello":
        print("Let's Start!")
        Name = input("What's Your Name?")
        Emoji = input("Please Type Up an Emoji via Windows + .:")
\\
        print("~ " + Emoji + " " + Name + "'s Idea Tracker")

        print("--------------------------------------------")

        Ideas = {
            "Idea_1": input("What's Your First Idea?"),
            "Idea_2": input("What's Your Second Idea?"),
            "Idea_3": input("What's Your Third Idea?"),
            "Idea_4": input("What's Your Fourth Idea?")
        }

        print("Idea 1: " + Ideas["Idea_1"])
        print("Idea 2: " + Ideas["Idea_2"])
        print("Idea 3: " + Ideas["Idea_3"])
        print("Idea 4: " + Ideas["Idea_4"])

        Ideasinput = input("Do you have more ideas? (Yes/No)")

        if Ideasinput.lower() == "yes":
            Ideas_no = input("Please Write Whether It's Three, Four, or Five:")

            if (Ideas_no == "Three"):
                Ideas["Idea_5"] = input("What's Your Fifth Idea?")
                print("Idea 5: " + Ideas["Idea_5"])
                Ideas["Idea_6"] = input("What's Your Sixth Idea?")
                print("Idea 6: " + Ideas["Idea_6"])
                Ideas["Idea_7"] = input("What's Your Seventh Idea?")
                print("Idea 7: " + Ideas["Idea_7"])

            elif (Ideas_no == "Four"):
                Ideas["Idea_5"] = input("What's Your Fifth Idea?")
                print("Idea 5: " + Ideas["Idea_5"])
                Ideas["Idea_6"] = input("What's Your Sixth Idea?")
                print("Idea 6: " + Ideas["Idea_6"])
                Ideas["Idea_7"] = input("What's Your Seventh Idea?")
                print("Idea 7: " + Ideas["Idea_7"])
                Ideas["Idea_8"] = input("What's Your Eighth Idea?")
                print("Idea 8: " + Ideas["Idea_8"])

            elif (Ideas_no == "Five"):
                Ideas["Idea_5"] = input("What's Your Fifth Idea?")
                print("Idea 5: " + Ideas["Idea_5"])
                Ideas["Idea_6"] = input("What's Your Sixth Idea?")
                print("Idea 6: " + Ideas["Idea_6"])
                Ideas["Idea_7"] = input("What's Your Seventh Idea?")
                print("Idea 7: " + Ideas["Idea_7"])
                Ideas["Idea_8"] = input("What's Your Eighth Idea?")
                print("Idea 8: " + Ideas["Idea_8"])
                Ideas["Idea_9"] = input("What's Your Ninth Idea?")
                print("Idea 9: " + Ideas["Idea_9"])

        else:
            print("You have your ideas!")

        Generating = input("Would you like to generate random ideas? (Yes/No)")

        if Generating.lower() == "yes":
            print("Generating Ideas...")
            # This line will cause an error if there are less than 9 ideas
            # print("Idea Selected: " + Emoji + " " + Ideas["Idea_1"])
            print("Idea Selected: " + Emoji + " " + Ideas.get("Idea_1", "No idea 1 found")) # Using .get for safer access

    else:
        print("Bye!")

elif (Tool == "Receipt Calculator"):
    print("Welcome To Your Receipt Calculator, Hosted by Rakshu Technologies")
    print("To Begin, Please Answer the Following Questions on Your Items:")

    Itemno = int(input("How Many Items Are You Buying? Please Answer Either 2, 3, or 4"))
    if (Itemno == 3):
        Item_3_1 = int(input("How Much Dollars is Your First Item?"))
        Item_3_2 = int(input("How Much Dollars is Your Second Item?"))
        Item_3_3 = int(input("How Much Dollars is Your Third Item?"))

        receipt = input("Do You Want To Checkout Your Receipt? Say 'Yes' or 'No'")

        if (receipt.lower() == "yes"):
            print(f"Your Receipt Is:" +
                  "_________________________________________" +
                  f"Item 1: {Item_3_1}")

    elif (Itemno == 2):
        Item_2_1 = int(input("How Much Dollars is Your First Item?"))
        Item_2_2 = int(input("How Much Dollars is Your Second Item?"))

    elif (Itemno == 4):
        Item_1 = int(input("How Much Dollars is Your Item?"))
        Item_2 = int(input("How Much Dollars is Your Next Item?"))
        Item_3 = int(input("How Much Dollars is Your Third Item?"))
        Item_4 = int(input("How Much Dollars is Your Next Item?"))
    else:
        print("Invalid number of items.")

else:
    print("Invalid tool selected. Directing you to Receipt Calculator.")
    print("Welcome To Your Receipt Calculator, Hosted by Rakshu Technologies")
    print("To Begin, Please Answer the Following Questions on Your Items:")

    Itemno = int(input("How Many Items Are You Buying? Please Answer Either 2, 3, or 4"))
    if (Itemno == 3):
        Item_3_1 = int(input("How Much Dollars is Your First Item?"))
        Item_3_2 = int(input("How Much Dollars is Your Second Item?"))
        Item_3_3 = int(input("How Much Dollars is Your Third Item?"))

        receipt = input("Do You Want To Checkout Your Receipt? Say 'Yes' or 'No'")

        if (receipt.lower() == "yes"):
            print(f"Your Receipt Is:" +
                  "_________________________________________" +
                  f"Item 1: {Item_3_1}")

    elif (Itemno == 2):
        Item_2_1 = int(input("How Much Dollars is Your First Item?"))
        Item_2_2 = int(input("How Much Dollars is Your Second Item?"))

    elif (Itemno == 4):
        Item_1 = int(input("How Much Dollars is Your Item?"))
        Item_2 = int(input("How Much Dollars is Your Next Item?"))
        Item_3 = int(input("How Much Dollars is Your Third Item?"))
        Item_4 = int(input("How Much Dollars is Your Next Item?"))
    else:
        print("Invalid number of items.")
