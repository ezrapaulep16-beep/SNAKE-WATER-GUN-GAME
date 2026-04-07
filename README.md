🐍💧🔫 SNAKE WATER GUN GAME 🔫💧🐍
=================================

A fun Python terminal game inspired by Rock-Paper-Scissors!

Snake drinks Water 🐍 > 💧  
Water damages Gun 💧 > 🔫  
Gun kills Snake 🔫 > 🐍 
 "cells": []
   "cell_type": "code",
   "execution_count": null,
   "id": "a5848b3f-8185-4361-b980-9755237bc007",
   "metadata": {},
   "outputs": [],
   "source": [
    "import random\n",
    "choices = ['snake','water','gun']\n",
    "while True:\n",
    "    user = input(\"\\nEnter your choice (snake,water,gun):\").lower()\n",
    "    if user == \"quit\":\n",
    "        print(\"Thanks for playing\")\n",
    "        break\n",
    "    \n",
    "    computer = random.choice(choices)\n",
    "    print(f'you chose: {user}')\n",
    "    print(f'computer chose:{computer}')\n",
    "    \n",
    "    if computer == user:\n",
    "        print('Its a tie!')\n",
    "    elif (user == \"snake\" and computer == \"water\") or \\\n",
    "         (user == \"gun\" and computer == \"snake\") or \\\n",
    "         (user == \"water\" and computer == \"gun\"):\n",
    "        print('You win!')\n",
    "    else:\n",
    "        print('You loose')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "dd1762b9-cb24-45ba-a435-ebc674d4a1b2",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:base] *",
   "language": "python",
   "name": "conda-base-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}





# 🐍💧🔫 Snake Water Gun Game

A fun and simple Python game based on the classic **Rock-Paper-Scissors** concept.

---

## 🎮 How to Play

* 🐍 Snake drinks Water → **Snake wins**
* 💧 Water damages Gun → **Water wins**
* 🔫 Gun kills Snake → **Gun wins**

---

## 🚀 Features

* Random computer choices 🤖
* Simple terminal gameplay 💻
* Beginner-friendly code 📘

---

## 🛠️ Installation

1. Install Python (3.x recommended)
2. Clone this repository:

```bash
git clone https://github.com/your-username/snake-water-gun.git
cd snake-water-gun
```

3. Run the game:

```bash
python game.py
```

---

## ▶️ Usage

Enter one of the following:

* `snake`
* `water`
* `gun`
* `quit` (to exit)

---

## 🧠 Example

```
Enter your choice: snake
You chose: snake
Computer chose: water
You win!
```

---

## 🔥 Future Improvements

* Add score tracking 🧮
* Build a GUI using Tkinter 🖥️
* Add sound effects 🔊
* Multiplayer mode 👥

---

## 🤝 Contributing

Feel free to fork this repo and improve the game!

---

## 📜 License

This project is open-source and free to use.
[snake ,gun and water.ipynb](https://github.com/user-attachments/files/26541947/snake.gun.and.water.ipynb){
