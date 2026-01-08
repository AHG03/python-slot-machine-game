# Python CLI Slot Machine

A classic, terminal-based slot machine simulation built with Python. This project features a complete game loop where players can manage a virtual balance, place bets, and win payouts based on randomized reel spins.

## 🕹️ Features

* **Dynamic Balance Management**: Players set their own starting capital and manage it throughout the session.
* **Input Validation**: Robust error handling ensures that only valid numbers and bet amounts within the player's balance are accepted.
* **Weighted Payout Logic**:
* **Jackpot**: Match all 3 symbols to win **10x** your bet.
* **Small Win**: Match any 2 symbols to win **2x** your bet.


* **Interactive Gameplay**: A continuous game loop that allows players to keep playing until they choose to walk away or run out of funds.

## 🚀 Getting Started

### Prerequisites

* Python 3.x installed on your machine.

### Installation & Running

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/python-slot-machine.git
cd python-slot-machine

```


2. **Run the game:**
```bash
python slot_machine.py

```



## 🛠️ Technical Details

The project is structured into modular functions for better readability and maintenance:

* `get_starting_balance()` & `get_bet_amount()`: Handle user interaction and data sanitization.
* `spin_reels()`: Uses Python's `random` module to generate outcomes.
* `calculate_payout()`: Contains the core game logic and win conditions.
* `main()`: Orchestrates the game flow and state updates.

## 📝 Example Gameplay

```text
Please enter your starting balance: $100
Welcome to Slot Machine Game!
You start with a balance of $100.

Current balance: $100
Enter your bet amount: $10
🍒 | 🍋 | 🍒
You won $20!
Do you want to play again? (y/n): y

```
