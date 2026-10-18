# python-fitness-tracker.
while True:
    print("FITNESS MENU")
    print("1. Check Step Goal")
    print("2. Calculate Calories")
    print("3. Water Intake")
    print("4. Exit")

    choice = int(input("Enter your choice:"))
    if choice == 1:
        steps = int(input("Enter steps : "))
        if steps >= 10000:
            print("Goal Achieved")
        else:
            print(" steps left is :", 10000 - steps)

    elif choice == 2:
        minutes = int(input("Enter how much time you walked minutes: "))
        calories = minutes * 5
        print("Calories burned:", calories)

    elif choice == 3:
        water = float(input("Enter water taken in a day : "))
        print("Water taken:", water, "litres fit man")

    elif choice == 4:
        print("Exiting the program.")
        break

    else:
        print("Invalid choice")
