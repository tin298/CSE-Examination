def gps_tracker():
    x, y = 0, 0  # Starting position
    print("Starting at position (0, 0). Enter N/S/E/W to move, or STOP to end.")

    while True:
        command = input("Enter direction: ").strip().lower()

        if command == "stop":
            break
        elif command in ["n", "north"]:
            y += 1
        elif command in ["s", "south"]:
            y -= 1
        elif command in ["e", "east"]:
            x += 1
        elif command in ["w", "west"]:
            x -= 1
        else:
            print("Invalid input. Please enter N, S, E, W or STOP.")
            continue

        print(f"Current position: ({x}, {y})")

    # Session ended
    print(f"\nFinal position: ({x}, {y})")
    if (x, y) == (0, 0):
        print("You returned to the origin (0, 0).")
    else:
        print("You did NOT return to the origin (0, 0).")

# Run the GPS tracker
gps_tracker()
