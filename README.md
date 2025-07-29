✅ C# Concepts & Projects (Game Dev Context)

🔹 1. Variables & Data Types
🎯 Project: "Player Stats Tracker"
 Create a simple console or Unity script that stores and displays:
Player name (string)


Health (int)


Speed (float)


IsAlive (bool)


Add print statements showing the values and what they mean in-game.

🔹 2. Operators
🎯 Project: "Battle Damage Calculator"
 Let the player and enemy have attack/defense values. Use +, -, *, /, and % to:
Calculate damage


Determine critical hit


Show updated health after attack



🔹 3. Conditionals
🎯 Project: "Dialogue Branching System"
 Simple branching text based on player's choices (if/else/switch).
 Example: If playerReputation > 50, NPC says “Welcome, hero!”

🔹 4. Loops
🎯 Project: "Enemy Spawner Simulator"
 Use a for loop to spawn 10 enemies.
 Use foreach to go through all enemies and print their health.
 Use while to simulate enemies attacking until player HP hits 0.

🔹 5. Comments
🎯 Project: "Refactor and Comment"
 Take one of your earlier scripts and:
Add // comments to explain each line


Add block comments (/* */) for method overviews



🔹 6. Classes & Objects
🎯 Project: "Weapon System"
 Make a Weapon class with damage, ammo, fireRate.
 Create multiple Weapon objects like pistol, rifle, and rocket launcher.
 Switch between them and simulate firing.

🔹 7. Methods/Functions
🎯 Project: "Health System"
 Make functions like:
TakeDamage(int amount)


Heal(int amount)


IsDead()


Call them inside a simulated battle script.

🔹 8. Fields & Properties
🎯 Project: "Bank Account Simulator"
 Have a class BankAccount with:
private float balance


public float Balance { get; private set; }


Add methods to deposit and withdraw with safeguards using properties.

🔹 9. Constructors
🎯 Project: "Enemy Generator"
 Define a constructor in the Enemy class:
public Enemy(string name, int hp) { ... }
Generate enemies with different stats via constructor calls.
🔹 10. Encapsulation
🎯 Project: "Inventory System"
 Make an Inventory class that has a private list of items.
 Use AddItem() and GetItems() methods to manage access.



🔹 11. Inheritance
🎯 Project: "Enemy Base Class"
 Create a base class Enemy, and subclasses Zombie, Skeleton, and Alien.
 Each has a different Attack() behavior.

🔹 12. Polymorphism
🎯 Project: "Combat Simulator with Overriding"
 Use the above Enemy classes.
 Override TakeDamage() for each to behave differently.
 Have a list of Enemy and loop through calling their methods.

🎯 Final Capstone Project: "2D Dungeon Escape"
Goal: Combine all concepts into a playable game.
✨ Features:
Player Stats (Variables, Fields)


Combat Mechanics (Operators, Methods, OOP)


Enemy Variants (Inheritance & Polymorphism)


Inventory or Key Items (Encapsulation)


Game Loops (Loops, Conditionals)


Interactive NPCs (Dialogue with Conditionals)


Commented Code (Documentation)


Tools:
Unity 2D Project


Free assets from Kenney.nl or [Itch.io]
