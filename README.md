# Romantic
A simple idea for choosing a romantic atmosphere

import time

def romantic_dinner():
    print("Welcome to the Romantic Dinner Simulator!")
    print("Let's set up the mood for your romantic evening.")

    light_option = input("Choose the lighting (dim/bright): ")
    music_option = input("Choose the music (jazz/classical): ")
    food_option = input("Choose the food (italian/french): ")

    print("\nPreparing your romantic dinner...\n")
    time.sleep(2)

    print("Dimming the lights...")
    time.sleep(1)

    if light_option == "dim":
        print("Lights dimmed.")
    elif light_option == "bright":
        print("Lights set to bright.")

    print("Playing romantic", music_option, "music...")
    time.sleep(1)

    print("Serving delicious", food_option, "cuisine...")
    time.sleep(2)

    print("\nEnjoy your romantic dinner!")

if __name__ == "__main__":
    romantic_dinner()
