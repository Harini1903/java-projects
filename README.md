Java Projects Collection
This repository contains two Java projects:

Currency Converter – A simple application to convert between different currencies.

Dino Game – A fun 2D game inspired by Chrome’s offline dinosaur runner.

📂 Project Structure
css
Copy
Edit
Java-Projects-Collection/
├── Currency_Converter/
│   ├── src/
│   │   ├── Currency.java
│   │   ├── CurrencyConverter.java
│   │   └── Main.java
│   └── README.md
│
└── Dino_Game_java/
    ├── src/
    │   ├── Cactus.java
    │   ├── Dinosaur.java
    │   ├── Game.java
    │   ├── GameManager.java
    │   ├── GamePanel.java
    │   ├── GameWindow.java
    │   └── InputHandler.java
    └── README.md
1️⃣ Currency Converter
📌 Overview
The Currency Converter is a Java-based tool that lets users convert between different currencies using fixed or real-time exchange rates (depending on implementation).

✨ Features
Convert between USD, EUR, GBP, INR, etc.

Console or GUI-based interface

Error handling for invalid input

Easy to update exchange rates

🛠 Requirements
Java JDK 8 or higher

Eclipse / IntelliJ / VS Code

🚀 How to Run in Eclipse
Open Eclipse

File → New → Java Project → Name it Currency_Converter

Create a package (e.g., converter)

Add all .java files into src/converter

Make sure your Main.java contains:

java
Copy
Edit
public static void main(String[] args) {
    new CurrencyConverter(); // or your main logic
}
Right-click Main.java → Run As → Java Application

💡 Example Output
yaml
Copy
Edit
Welcome to Currency Converter
Enter amount in USD: 100
Choose target currency: EUR
Converted Amount: 91.50 EUR
2️⃣ Dino Game
📌 Overview
The Dino Game is a Java Swing-based clone of the Chrome offline dinosaur runner game.
Jump over obstacles and survive as long as possible.

✨ Features
Java Swing GUI

Character movement & jump mechanics

Collision detection

Increasing difficulty

🛠 Requirements
Java JDK 8 or higher

Eclipse IDE

🚀 How to Run in Eclipse
Open Eclipse

File → New → Java Project → Name it Dino_Game_java

Create a package named exactly:

java
Copy
Edit
package Dino_Game_java;
Add all .java files from Dino_Game_java folder into src/Dino_Game_java

Create or open a Main class:

java
Copy
Edit
package Dino_Game_java;

public class Main {
    public static void main(String[] args) {
        new GameWindow(); // Starts the game
    }
}
Right-click Main.java → Run As → Java Application
