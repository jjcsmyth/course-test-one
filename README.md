print("The tale of the goblin child adventures.")
keep_going = True

while keep_going:
    print(" Welcome, before we begin our adventure there is some questions first.")
    print(" Please press the enter key after you answer each question")
    userName = input("\nWhat is your name?:  ")
    while (len(userName) == 0):
        userName = input("\nWhat is your name?:  ")
    print("\nHello, " + userName + ". Pleased to meet you!")
    print("\n")
    userCity = input("\nWhat city do you live in? ")
    while (len(userCity) == 0):
        userCity = input("\nWhat city do you live in? ")
    userColor = input("\nWhat is your favorite color? ")
    while (len(userColor) ==0):
        userColor = input("\nWhat is your favorite color? ")
    userGender = input("\nWhich gender would you like to use? Enter boy, or girl: ")
    while userGender.lower() != "boy" and userGender.lower() != "girl":
        userGender = input("\nWhich gender would you like to use? Enter boy, or girl: ")
    userFood = input("\nWhat is your favorite food? ")
    while (len(userFood) == 0):
        userFood = input("\nWhat is your favorite food? ")

    print("\n")
    print(" Great let us begin our adventure")
    print("\n")
    print("In a realm unknown to humans, mythical creatures live just like them.")
    print("On an Earth that looks like what we know live unicorns, fairies, trolls, dragons, sprites,")
    print("goblins, and other mythical beings. In a city known as " + userCity + " lives a family of goblins.")
    print("A caring mother, a hard-working father, and a little " + userGender + " goblin.")
    print("\n")
    print("One day the parents had to run to town to fetch ingredients for that night's dinner.")
    print("They were thinking nothing about leaving the little " + userGender + " goblin alone for a short time.")
    print("The parents left the goblin kid alone, whose name was " + userName + " and that's where the adventure begins.")
    print("\n")
    print("Lost in thought " + userName + " did not know what to do but just so happened to look out the back window")
    print("and saw a forest glowing with " + userColor + " lights to the leftside and on the rightside a rock with")
    print("a hole in it that had a shining light coming out of the hole. " + userName + " the goblin, was not sure")
    print("what to do or think. " + userName + " the goblin child decides to go outside")

    print("\n")
    print("decides to wander into the backyard to explore. Which way will the goblin go left or right?")
    user_direction = input(' select left or right:')
    while user_direction.lower() != "left" and user_direction.lower() != "right":
        user_direction = input(' select left or right:')
    if user_direction == "left":
        print("\n")
        print("Looking toward the faerie forest was too tempting. " + userName + " decided to")
        print("go into the forest where the goblin " + userGender + " was met with the sight")
        print("of many glowing "  + userColor + " lights. Going deeper into the forest")
        print("it started to become darker and darker until the goblin kid came across a faerie village")
        print("Looking at the village in awe the goblin child did not know where to go" )
        print("Which way will the goblin child go the high road or the low road?")
        user_pathway = input(' select high road or low road: ')
        while user_pathway.lower() != "high road" and user_pathway.lower() != "low road":
          user_pathway = input(' select high road or low road: ')
    if user_pathway == "low road":
        print("\n")
        print("not looking where " + userName + " was going tripped over a wagon and came crashing down destroying")
        print("the village outer wall. The faeries became enraged and chased " + userName + " the goblin child back out")
        print("of the forest. " + userName + " was soo frightined and ran back inside the house just in time for")
        print("mom and dad to get home. later that evening the goblin family sat down to eat " + userFood + " and")
        print("they began to talk about the backyard and what was beyond. The goblin childs parents at that")
        print("point told the goblin child about the dangers beyond the backyard and to never venture beyond the backyard")
        print("---------------------The end----------------------------------------------------------------------")
        keep_going = True

        while keep_going:


            print("Would you like to continue your journey?")

            yes_or_no = input("To continue select (yes/no)? ")

            keep_going = yes_or_no.lower() == "yes"

    elif user_pathway == "high road":
        print("\n")
        print("the " + userGender + " goblin decided to take the high road and was met by a family of friendly")
        print("faeries who then told " + userName + " about life living amoungst the faeries and how wonderful life was")
        print("After some time " + userName + " the goblin child became hungry and feeling humble by the experiance asks")
        print("the faerie family for some food in the most polite manner. The faeries come back after a short time")
        print("with some " + userFood + " The goblin child started eating and striking up another conversation.")
        print("lossing track of the time " + userName + " noticed it was night now and said goodbye to the fairy village")
        print("and started running back through the forest glowing with " + userColor + " lights. " + userName + " ran soo")
        print("fast the " + userGender + " goblin slammed the back door when coming back into the goblin household.")
        print("the goblin child was met with a mom and dad goblin glaring mad back at " + userName + " the goblin child.")
        print("the parents being soo mad could only say the words room no dinner.")
        print("---------------------The end----------------------------------------------------------------------")
        keep_going = True

        while keep_going:


            print("Would you like to continue your journey?")

            yes_or_no = input("To conitue select (yes/no)? ")

            keep_going = yes_or_no.lower() == "yes"

    elif user_direction == "right":
        print("\n")
        print("The light coming from the cave has captivated the goblin child tempting " + userName + " to enter the")
        print("hole in the rock slipping inside the goblin child is met with a blinding light.")
        print("Having no choice but to move along one side of the cave which side should " + userName + " hold on to?")
        user_side = input(' select smooth side or rough side: ')
        while user_side.lower() != "smooth side" and user_side.lower() != "rough side":
                user_side = input(' select smooth side or rough side: ')
        if user_side == "smooth side":
            print("\n")
            print("the goblin child decided to move along the smooth side until the " + userGender + " goblin")
            print("is blinded no more but met with the")
            print("sight of a underground lake with a " + userColor + " crystal floating in the middle.") 
            print("Amazed by the crystal " + userName + " begins to gasp. The crystal becomes startled by the sound")
            print("and begins to speak ""who are you"" the crystal ask's and from that point they begin to strike up a")
            print("conversation. Afetr a while the goblin child becomes hungry and with the " + userGender + " goblins") 
            print("stomach growling loud enough the crystal ask's what was that sound? the goblin child tells the crystal")
            print("that was their stomach. The crystal reading the childs mind makes " + userFood + " appear.")
            print("After eating the goblin child begins to realize that it is getting late and starts to worry")
            print("about getting into trouble. Being soo scarred what will " + userName + " decide? leave to explore")
            print("distant lands instead of facing the goblin child's parents or go home to face the music?")
            user_choice = input("what will the goblin child do? Go home or continue to explore?: ")
            while user_choice.lower() != "go home" and user_choice.lower() != "continue to explore":
                user_choice = input("what will the goblin child do? go home or continue to explore?: ")
    if user_choice == "go home":
        print("Thinking how much " + userName + " would miss being home, the goblin child decides to run home.")
        print("---------------------The end----------------------------------------------------------------------")
        keep_going = True

        while keep_going:


            print("Would you like to continue your journey?")

            yes_or_no = input("To continue select (yes/no)? ")

            keep_going = yes_or_no.lower() == "yes"

        
    elif user_choice == "continue to explore":
        print("Now that the little goblin has seen what is beyond the backyard " + userName + " decided to")
        print("keep exploring what the world has to offer till eventually ending off in some far away")
        print("lands to become a merchant.")
        print("---------------------The end----------------------------------------------------------------------")
        keep_going = True

        while keep_going:


            print("Would you like to continue your journey?")

            yes_or_no = input("To continue select (yes/no)? ")

            keep_going = yes_or_no.lower() == "yes"


    elif user_side == "rough side":
        print("\n")
        print("The goblin child decides to grab onto the rough side of the cave and follows it until rushing water")
        print("is heard.Not being able to see where the " + userGender + " is going ends up slipping off the")
        print("edge falling into an undergound water-way that leads to " + userCity + " central fountain")
        print("which becomes plugged up then eventually burst forcing " + userName + " the poor goblin child")
        print("through the air and just so happens to fall right into the " + userGender + " parents lap.")
        print("Now with the goblin childs parents in shock both the mother look at " + userName + " wondering") 
        print("what events took place for their goblin child to fall on their laps.")
        print("Both the parents looking over the goblin child are thankful that at least " + userName + " was not")
        print("hurt. Bringing our adventure to an end.")
        print("---------------------The end----------------------------------------------------------------------")


keep_going = True

while keep_going:


    print("Would you like to continue your journey?")

    yes_or_no = input("To continue select (yes/no)? ")

    keep_going = yes_or_no.lower() == "yes"
