# Chess Move Bot

A modern chess analysis bot with a clean Tkinter GUI, powered by the Stockfish engine (GPLv3).  
It highlights the best three moves, shows shared origins and destinations with split borders/dots, and provides smooth, time‑based engine analysis.

---

## 🧠 Features

- **Best Move** highlighted in green  
- **Second Best Move** highlighted in orange  
- **Third Best Move** highlighted in red  
- **Split borders** when multiple moves originate from the same square  
- **Split dots** when multiple moves target the same square  
- **Promotion dialog** (Queen, Rook, Bishop, Knight)  
- **Undo function**  
- **Smooth engine analysis** (time‑based, no stuttering)  
- **Clean Tkinter GUI**  
- **Board flip support** (white bottom / black bottom)  
- **Easy to use, beginner‑friendly interface**

---

## ⚙️ Installation (Source Version)

### 1. Install Python  
Download Python 3.10+ from:  
https://www.python.org/downloads/

Make sure to enable:  
✔ “Add Python to PATH”

---

### 2. Download the source code  
Clone the repository or download it as ZIP:

```bash
git clone https://github.com/CretoraForge/chess-move-bot
Or click Code → Download ZIP on GitHub.

3. Install required packages
Open a terminal inside the project folder and run:

bash
pip install -r requirements.txt
This installs:

python-chess (engine + board logic)

tk (Tkinter GUI)

4. Run the bot
bash
python src/chess_bot.py
The GUI will open and you can start analyzing moves immediately.

📦 Download (EXE Version)
The executable version with installer is available here:

👉 Gumroad: Coming soon
