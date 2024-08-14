import random

def adventure_game():
    print("Welcome to the Mystic Forest Adventure!")
    print("You find yourself at the entrance of a dark, mysterious forest.")
    
    player_health = 100
    items = []

    while True:
        print("\nWhat would you like to do?")
        print("1. Explore deeper into the forest")
        print("2. Search for items")
        print("3. Check your status")
        print("4. Exit the forest (end game)")
        
        choice = input("Enter your choice (1-4): ")
        
        if choice == '1':
            explore_forest(player_health, items)
        elif choice == '2':
            search_items(items)
        elif choice == '3':
            check_status(player_health, items)
        elif choice == '4':
            print("You decide to leave the forest. Thanks for playing!")
            break
        else:
            print("Invalid choice. Please try again.")

def explore_forest(health, items):
    events = ["You encounter a friendly fairy!", "You stumble upon a hidden treasure!",
              "A mischievous goblin appears!", "You find a healing spring!"]
    event = random.choice(events)
    print(event)
    # Add more complex logic here for each event

def search_items(items):
    new_item = random.choice(["Magic Wand", "Health Potion", "Ancient Map", "Enchanted Sword"])
    print(f"You found a {new_item}!")
    items.append(new_item)

def check_status(health, items):
    print(f"Health: {health}")
    print("Items:", ", ".join(items) if items else "No items")

if __name__ == "__main__":
    adventure_game()
