# 🎮 Tic Tac Toe in Python (Tkinter)

A simple yet fun **Tic Tac Toe** game built using **Python** and **Tkinter** GUI library.  
By running this note book, you can play against the computer in two difficulty modes:  
- **Easy Mode** 🎲 (Random AI) — computer makes random moves and it is easy for the human player to win.
- **Advanced Mode** 🧠 (Minimax AI) — computer plays perfectly using the Minimax algorithm and it is nearly impossible for the human player to win. The Minimax algorithm makes the AI player undefeatable.

## ✨ Features

- Click-based gameplay with Tkinter buttons.
-  **Easy Mode**: Computer chooses random empty spots.
-  **Advanced Mode**: Computer uses **Minimax** algorithm to make optimal moves.
-  **Mode selection popup** at the start: "Are you ready?? Choose the mode"
-  Automatic reset after win/draw.

## 📂 Project Structure
```
tic-tac-toe-tkinter.ipynb   # Final Python/Tkinter game code in Jupyter Notebook
```

## 🧠 Minimax Algorithm Overview

The **Minimax** algorithm is used in Advanced Mode to simulate all possible moves and choose the best one, assuming the opponent plays optimally.

Scoring:
- `+1` → AI wins
- `-1` → Player wins
- `0` → Draw

The algorithm recursively evaluates all possible game states, alternating between:
- **Maximizing** player (AI — tries to maximize score)
- **Minimizing** player (Human — tries to minimize AI's score)

## 🔍 How Minimax Works?

```
          AI Turn (Maximize)
              +----+----+
             /           \
       Move 1             Move 2
     (score ?)          (score ?)
      /   \               /   \
Player  Player       Player  Player
(Min)   (Min)        (Min)   (Min)
```

1. AI looks at all possible moves.  
2. For each move, it simulates the human's response.  
3. The human chooses moves that are worst for the AI (minimizing score).  
4. AI chooses the move that leads to the best possible outcome (maximizing score).  


## 🖼 Game Board Looks Like

### Mode Selection
<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/a8c79f39-d76f-48c2-a08f-e653ee96ae67" />


### Gameplay
<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/231ff01c-b600-4bc5-b9cc-52caf7981abd" />
<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/2b28699b-a8b8-4b56-9900-2b27a8a3620f" />
<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/cd895522-6238-45ef-a64b-8c80204a6ba5" />
<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/a221258e-b2b5-4132-83af-00e136fb7d4c" />


## 🔮 Future Improvements

- Use sample game moves data to train a Machine Learning model for the AI player to make each move.
- Add a scoreboard to track wins.
- Make the board resizable and mobile-friendly.

---


