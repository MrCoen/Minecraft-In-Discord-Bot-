# Minecraft Discord Bot

Welcome to the Minecraft Discord Bot! This bot enhances your Minecraft experience by providing various commands to interact with an in-game profile, explore new biomes, mine resources, and more. This README will guide you through the features and commands of the bot.

## Features

- **Start Your Journey**: Create and manage your Minecraft profile with unique coordinates, biomes, and inventories.
- **Explore New Biomes**: Discover new biomes and structures, and collect rare items.
- **Manage Inventory**: Check your inventory and manage your resources.
- **Mining**: Start mining sessions to gather resources.
- **Sell Items**: Sell items from your inventory to earn in-game currency.
- **View Profile**: Check your in-game profile including coordinates, biome, mining status, and net worth.

## Commands

### /minecraft start

**Description**: Start your Minecraft journey by creating a new profile.

**Usage**:

/minecraft start --name <name> --description <description>

markdown

- `name`: Your character's name (required).
- `description`: Description of your character (optional).

**Example**:

/minecraft start --name Steve --description "Brave adventurer of the Overworld"




### /minecraft explore

**Description**: Explore new biomes and structures.

**Usage**:

/minecraft explore




### /minecraft inventory

**Description**: Check your inventory.

**Usage**:

/minecraft inventory




### /minecraft profile

**Description**: View your in-game profile.

**Usage**:

/minecraft profile




### /minecraft mine

**Description**: Start a mining session.

**Usage**:

/minecraft mine --duration <duration>

markdown

- `duration`: Duration of mining in seconds (required).

**Example**:

/minecraft mine --duration 60




### /minecraft sell

**Description**: Sell items from your inventory.

**Usage**:

/minecraft sell --item <item_id> --amount <amount>

markdown

- `item_id`: The ID of the item to sell (required).
- `amount`: The amount of the item to sell (required).

**Example**:

/minecraft sell --item diamond --amount 3

perl


## Detailed Features

### Starting Your Journey

When you use the `/minecraft start` command, the bot creates a new profile for you with a unique ID and random coordinates. You are assigned a random biome, and you start with an empty inventory. This command can only be used once per user.

### Exploring New Biomes

The `/minecraft explore` command allows you to discover new biomes and structures. You have a 10% chance to find a structure, and if you do, you may find rare items in chests within that structure.

### Managing Inventory

You can check your inventory at any time with the `/minecraft inventory` command. The bot will list all the items you have collected so far.

### Mining for Resources

The `/minecraft mine` command lets you start a mining session. Specify the duration, and the bot will simulate a mining expedition. After the time elapses, you receive a random amount of various mineable items.

### Selling Items

Use the `/minecraft sell` command to sell items from your inventory. You can specify the item and the amount you want to sell. The bot calculates the total price based on predefined item prices and updates your balance accordingly.

### Viewing Your Profile

The `/minecraft profile` command provides a detailed view of your in-game profile, including your balance, net worth, coordinates, biome, mining status, and more. This helps you keep track of your progress and current status in the game.

## Installation and Setup

1. Clone the repository:
    ```
    git clone <repository-url>
    ```

2. Install the dependencies:
    ```
    npm install
    ```

3. Set up your environment variables (if necessary):
    ```
    DISCORD_TOKEN=your_discord_token
    ```

4. Run the bot:
    ```
    node index.js
    ```

## Contribution

Feel free to contribute to this project by opening issues or submitting pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License.

---

By using this bot, you can immerse yourself in a Minecraft-themed adventure within your Discord server. Happy mining and exploring!
