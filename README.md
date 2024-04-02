# happiness
def main():
    print("Rate your happiness on a scale from 1 to 10:")
    try:
        happiness = int(input("> "))
        if happiness < 1 or happiness > 10:
            print("Please enter a number between 1 and 10.")
            return
        if happiness >= 8:
            print("That's great to hear! Keep up the positivity!")
        elif happiness >= 5:
            print("It's good to know you're doing okay. Things will get better!")
        else:
            print("I'm sorry to hear that. Remember, tough times don't last forever. Stay strong!")
    except ValueError:
        print("Please enter a valid number.")

if __name__ == "__main__":
    main()
