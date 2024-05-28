Python OOP Battle Game
Welcome to the Python OOP Battle Game! This game is a simple turn-based battle simulator built using Object-Oriented Programming (OOP) principles in Python. Players can control a hero character and battle against an enemy, utilizing normal and special attacks. The game demonstrates the use of encapsulation, inheritance, and polymorphism in a fun and interactive way.

Features
Encapsulation: Each character's attributes are protected and accessed through getter methods.
Inheritance: The Heroi and Inimigo classes inherit from the Personagem base class.
Polymorphism: Methods are overridden in the derived classes to provide specialized behavior.
Classes
Personagem
The base class for all characters in the game. It encapsulates common attributes and methods such as:

nome: The name of the character.
vida: The health of the character.
nivel: The level of the character.
atacar(): Method to attack another character.
receber_ataque(): Method to receive damage from an attack.
exibir_detalhes(): Method to display character details.
Heroi
A subclass of Personagem representing the hero controlled by the player. Additional attribute:

habilidade: Special ability of the hero.
Additional methods:

ataque_especial(): Method to perform a special attack causing increased damage.
Inimigo
A subclass of Personagem representing the enemy character. Additional attribute:

tipo: Type of the enemy.
Jogo
The main class orchestrating the game. It manages the battle between the hero and the enemy.

How to Play
Start the Game: Create an instance of the Jogo class and call the iniciar_batalha() method.
Battle Turns: The game progresses in turns where the player can choose between a normal attack and a special attack.
Victory Conditions: The battle continues until either the hero or the enemy's health reaches zero. The player wins if the hero's health is above zero at the end of the battle.
