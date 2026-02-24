# 🎯 Digit Match

> *Can you crack the secret number before you run out of tries?*

Digit Match is a number-guessing game where you use logic and deduction to figure out a hidden number — one guess at a time. Play solo, challenge an AI, or go head-to-head with a friend.

---

## 🕹️ How to Play

1. **Choose your settings** — pick the number of digits (2–5), attempt limit, mode, and difficulty.
2. **A secret number is generated** (or set by your opponent in 2-player mode).
3. **Enter your guess.** After each attempt, you'll get feedback showing how many digits matched.
4. **Use the clues** to narrow it down and crack the code!
5. First to guess the secret number wins. If attempts run out — the number wins. 💥

---

## 🔢 Digit Matching Rules

A digit **matches** when it is the **correct number in the correct position**.

**Example** — Secret is `4821`, you guess `1234`:
- `2` is in position 3 of both → ✅ match
- All other digits are wrong position or wrong number → ❌
- Result: **1/4 matched**

> ⚠️ Only *exact position* counts. A digit that appears in the number but in the wrong spot does **not** score a match.

---

## ⚙️ Settings

### Number of Digits
| Setting | Range | Difficulty |
|---------|-------|------------|
| 2 digits | 1 – 99 | Beginner |
| 3 digits | 1 – 999 | Easy |
| 4 digits | 1 – 9999 | Medium |
| 5 digits | 1 – 99999 | Hard |

### Attempts
- **∞ Unlimited** — Keep guessing until you crack it. No pressure.
- **🔢 Limited** — Choose 3 to 20 attempts. Run out and the secret wins.

### Game Mode
- **🧠 Solo** — You vs. a randomly generated secret number.
- **🤖 vs AI** — You and the AI each hold a secret. Take turns guessing. First to crack the other's number wins.
- **👥 2 Player** — P1 and P2 each set a secret number (privately), then take turns guessing. Play on the same device, passing it back and forth.

### Difficulty
- **😊 Easy** — After each guess, the matching digits **light up** so you know exactly which positions are correct.
- **💀 Hard** — You only see the **count** of matched digits, not which ones. Pure deduction.

---

## 🤖 vs AI Rules

- Both players (you and the AI) secretly choose a number at the start.
- You guess the AI's number; the AI guesses yours — **alternating turns**.
- The AI uses an elimination algorithm: it tracks all your previous feedback and only guesses numbers that are still mathematically possible.
- First to fully match all digits wins. If both exhaust limited attempts without cracking the code, it's a **draw**.

---

## 👥 2 Player Rules

1. **P1** enters their secret number privately (P2 looks away), then locks it in.
2. **P2** enters their secret number privately (P1 looks away), then locks it in.
3. **P1 goes first** — guesses P2's number. P2 is shown the match count (and which digits in Easy mode).
4. **P2 takes their turn** — guesses P1's number.
5. Keep alternating until someone cracks the code — or both run out of tries.

---

## 💡 Strategy Tips

- **Start broad** — your first guess should spread digits across different values to maximize information.
- **In Easy mode**, pay attention to which *positions* light up, not just how many.
- **In Hard mode**, treat it like Mastermind — use process of elimination across multiple guesses.
- **Against the AI**, the AI never wastes a guess. It will close in quickly on longer digit modes.
- **In 2 Player**, avoid obvious numbers like `1111` or `1234` — your opponent will crack those fast.

---

## 🎨 Themes

| Theme | Vibe |
|-------|------|
| **Cosmic** | Deep purple & gold. Classic space energy. |
| **Neon** | Electric green & hot pink. Arcade mode. |
| **Lava** | Fiery red & yellow. Play with heat. |

---

## 🌏 Language Support

The game automatically switches to **Chinese (中文)** if your browser language is set to Chinese. All UI text, instructions, and buttons are fully localized.

---

## 🚀 Play It

👉 **[Play Digit Match](https://yourusername.github.io/digit-match)**

*(Replace the link above with your actual GitHub Pages URL)*
