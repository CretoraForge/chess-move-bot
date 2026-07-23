# Chess Move Bot

A modern chess analysis bot with a clean Tkinter GUI, powered by the Stockfish engine (GPLv3).  
It highlights the best three moves, shows shared origins and destinations with split borders/dots, and provides a smooth, time‑based analysis experience.

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
- **Supports flipping the board (top/bottom start)**  

---

## ⚙️ Installation (Source Version)

```bash
pip install -r requirements.txt
python src/chess_bot.py
