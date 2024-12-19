print("---------------------------------SURVIVE THE ISLAND---------------------------------")

print("DAY 1")
print("\nDue to a storm, your ship crashes on an unknown island in the middle of the sea")
print("The island has a large forest, there will certainly be different kinds of flora and fauna in the forest")
print("There are also chances of some fishes around the shore")
print("Luckily, you still got your backpack with you with all the things intact due to the plastic cover")

print("\n1. Go into the forest and search for food\n2. Set up a tent and use your fishing rod to catch fishes")
routes = int(input("Choose carefully: "))

if routes == 1:
    print("\nYou got lost in the forest")

    traceback = int(input("You have 2 options:\n1. Traceback your footsteps\n2. Venture to search for some fruits: "))
    if traceback == 2:
        print("\nYou got eaten by a group wild creatures")
    elif traceback == 1:
        print("\nYou somehow managed to arrive back at your destination")
        print("You got some fishes after waiting patiently for 2 hours, these will be enough for 2 days")
        print("\nThe weather is cold so you have to warm yourself up")
        warm_1 = int(
            input("1. Make a fire using the trash material you have\n2. Stay in your tent and blow on your hands: "))

        if warm_1 == 1:
            print("You can now warm yourself up and spend the night in ease")

            print("\nDAY 2")
            wait_1 = int(input("1. Roam the island until help arrives\n2. Write messages on the sand to send SOS signals: "))
            if wait_1 == 1:
                print("\nYou eventually ran out of resources and died of starvation or got eaten by wildings")
            elif wait_1 == 2:
                print("\nHelp arrived and you managed to escape")
                print("Conratulations! You managed to survived and beat the game")
            else:
                print("Invalid choice")
        elif warm_1 == 2:
            print("\nYou died of pneumonia due to the severe cold")

        else:
            print("Invalid choice")
    else:
        print("Invalid choice")

elif routes == 2:
    print("\nYou got some fishes after waiting patiently for 2 hours, these will be enough for 2 days")
    print("\nThe weather is cold so you have to warm yourself up")
    warm_2 = int(input("1. Make a fire using the trash material you have\n2. Stay in your tent and blow on your hands: "))

    if warm_2 == 1:
        print("You can now warm yourself up and spend the night in ease")

        print("\nDAY 2")
        wait_2 = int(input("1. Roam the island until help arrives\n2. Write messages on the sand to send SOS signals: "))
        if wait_2 == 1:
            print("\nYou eventually ran out of resources and died of starvation or got eaten by wildings")
        elif wait_2 == 2:
            print("\nHelp arrived and you managed to escape")
            print("Conratulations! You managed to survived and beat the game")
        else:
            print("Invalid choice")

    elif warm_2 == 2:
        print("\nYou died of pneumonia due to the severe cold")
    else:
        print("Invalid choice")

else:
    print("Invalid choice")