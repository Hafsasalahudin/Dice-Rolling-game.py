import random

playing = True
while playing:
    choice = input("Roll the dice? (y/n) ").lower() 

    if choice == 'y':
        die_1 = random.randint(1, 6)
        die_2 = random.randint(1, 6)
        print(f"({die_1},{die_2})")
    elif choice == 'n':
        print("Thanks for playing! :)")
        playing = False
    else:
        print("Invalid choice!")
