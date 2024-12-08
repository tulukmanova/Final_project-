#Takhmina 
#11/27/24

def chapter_one():
    print("\n--- Chapter 1: The Town of Pary ---")
    print("Strange hints of a curse and mysterious disappearances are reported in the town.")
    
    # Player choices
    print("\nYour options:")
    print("1. Meet locals to learn basic survival skills.")
    print("2. Discover clues about your hidden abilities.")
    print("3. Decide whether to keep secrets or ask for help.")

    choice = input("What will you do? (1/2/3): ").strip()

    if choice == "1":
        print("\nYou meet the town blacksmith and learn basic survival skills.")
        print("You feel more prepared for what lies ahead.")
        return chapter_two()
    elif choice == "2":
        print("\nYou investigate and discover strange symbols near the forest.")
        print("These symbols hint at your hidden powers.")
        return chapter_two()
    elif choice == "3":
        print("\nYou reveal the symbols to the village elder.")
        print("The elder warns you of risks but offers valuable advice.")
        return chapter_two()
    else:
        print("\nInvalid choice. Try again.")
        return chapter_one()

def chapter_two():
    print("\n--- Chapter 2: The Mystical Forest ---")
    print("You enter the mystical forest filled with enchanted traps and supernatural creatures.")
    print("A mysterious guide appears and offers to help you.")

    # Player choices
    print("\nYour options:")
    print("1. Follow the guide's advice for safe passage.")
    print("2. Explore the forest alone, risking danger.")

    choice = input("What will you do? (1/2): ").strip()

    if choice == "1":
        print("\nThe guide leads you safely through the forest, but it takes longer.")
        print("You gain valuable insights but lose some energy.")
        return chapter_three()
    elif choice == "2":
        print("\nYou venture alone and face supernatural creatures!")
        print("You risk health but gain more experience.")
        return chapter_three()
    else:
        print("\nInvalid choice. Try again.")
        return chapter_two()

def chapter_three():
    print("\n--- Chapter 3: The Ancient Ruins ---")
    print("You arrive at the ancient ruins, uncovering secrets about your ancestry and the curse.")
    print("The ruins are guarded by enchanted statues, and riddles block your path.")

    # Player choices
    print("\nYour options:")
    print("1. Solve riddles and face the guardians to unlock your powers.")
    print("2. Use forbidden power to bypass the obstacles quickly.")

    choice = input("What will you do? (1/2): ").strip()

    if choice == "1":
        print("\nYou solve riddles and gain new abilities!")
        print("The guardians allow you to pass.")
        return chapter_four()
    elif choice == "2":
        print("\nYou tap into forbidden power and bypass the obstacles.")
        print("A dark aura surrounds you as the curse begins to take hold.")
        return chapter_four()
    else:
        print("\nInvalid choice. Try again.")
        return chapter_three()

def chapter_four():
    print("\n--- Chapter 4: The Enchanted Water Source ---")
    print("You reach a shimmering water source that holds secrets about the curse and your fate.")
    print("Spectral creatures linger nearby, watching your every move.")

    # Player choices
    print("\nYour options:")
    print("1. Rest at the water source to regain energy.")
    print("2. Investigate the water's whispers to learn more about the curse.")
    print("3. Push forward to save time and find the final battleground.")

    choice = input("What will you do? (1/2/3): ").strip()

    if choice == "1":
        print("\nYou rest by the water and regain strength.")
        print("The spectral creatures grow restless.")
        return chapter_three()  # Loop back to Chapter 3
    elif choice == "2":
        print("\nThe water reveals the location of the final battleground and your role in lifting the curse.")
        print("You gain critical knowledge but attract the spectral creatures' attention.")
        return chapter_five()
    elif choice == "3":
        print("\nYou push forward without resting.")
        print("You conserve time but miss crucial insights about the curse.")
        return chapter_five()
    else:
        print("\nInvalid choice. Try again.")
        return chapter_four()

def chapter_five():
    print("\n--- Chapter 5: The Final Battle ---")
    print("The battlefield is shrouded in darkness, with the ancient evil waiting ahead.")
    print("Your decisions so far will determine your abilities in this final confrontation.")

    # Player choices
    print("\nYour options:")
    print("1. Use all acquired abilities and allies in combat.")
    print("2. Unlock forbidden power for a decisive attack.")
    print("3. Attempt to negotiate with the ancient evil.")

    choice = input("What will you do? (1/2/3): ").strip()

    if choice == "1":
        print("\nYou rally your allies and channel all your abilities into combat.")
        print("The ancient evil is defeated, and the curse is lifted!")
        print("Pary is free.")
    elif choice == "2":
        print("\nYou unleash forbidden power, destroying the ancient evil.")
        print("The curse binds you to Pary as its eternal guardian.")
        print("Pary is safe, but at great personal cost.")
    elif choice == "3":
        print("\nYou attempt to reason with the ancient evil, but it rejects your offer.")
        print("Unprepared for battle, you are overwhelmed, and Pary remains cursed.")
    else:
        print("\nInvalid choice. Try again.")
        return chapter_five()

# Start the game
chapter_one()
