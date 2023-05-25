# TemplateTerminalGame


# Player Battle Game

This is a simple text-based battle game implemented in JavaScript. Players can create characters and use different skills to attack each other. The game continues until one of the players' health reaches zero.


## How to Play

1. When prompted, enter the names of the skills you want each player to learn. Choose from the predefined skill list provided in the code.

2. After both players have learned their skills, the battle begins.

3. Each player takes turns attacking the other by entering the name of the skill they want to use.

4. The game continues until one of the players' health reaches zero.

## Customization

You can customize the game by modifying the predefined skill list and adjusting the initial player attributes such as health, energy, and armor. These changes can be made in the code by modifying the values of the skill objects and the `Player` class constructor.

## Skills

Skills are defined as objects with the following properties:

- `damage`: The amount of damage the skill inflicts on the target.
- `penetration`: The armor penetration value of the skill.
- `heal`: The amount of health the player gains when using the skill.
- `cost`: The amount of energy required to use the skill.
- `desc`: A description of the skill.

Feel free to modify the existing skills or add new skills to the predefined skill list.

## Class Structure

The game utilizes a `Player` class to represent each player. Each player has attributes such as health, energy, armor, and learned skills. The `Player` class also contains methods for performing attacks, updating health and energy, and managing the game flow.



