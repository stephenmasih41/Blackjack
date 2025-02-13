# 🃏 Blackjack Game

## 🎮 Overview

This is a simple Blackjack game built using HTML, CSS, and JavaScript. The game allows the player to draw cards, calculate their sum, and determine if they have won, lost, or should draw another card.

## 🔥 How to Play

- 1️⃣ Click the START GAME button to begin a new round.
- 2️⃣ Two random cards will be drawn, and their sum will be displayed.
- 3️⃣ If the sum is 21, you win with a Blackjack 🎉.
- 4️⃣ If the sum is less than 21, you can click NEW CARD to draw another card.
- 5️⃣ If the sum exceeds 21, you lose the game ❌.

## ✨ Features

- ✅ Generates random cards (Ace counts as 11, face cards count as 10).
- ✅ Displays the current hand and total sum.
- ✅ Checks game conditions and displays messages accordingly.
- ✅ Keeps track of the player's chips.

## 🏗 Tech Stack

- 🏷 HTML - Structure of the game UI

- 🎨 CSS - Styling and layout (if added)

- ⚡ JavaScript - Game logic and interactivity

## 📌 JavaScript Logic (index.js)

### 🏗 Variables:

- 👤 player: An object storing the player's name and chips.

- 🎴 cards: An array holding the cards in hand.

- ➕ sum: The total sum of the cards.

- 🏆 hasBlackJack: Boolean to check if the player has won.

- 🚀 isAlive: Boolean to track if the player is still in the game.

- 💬 message: Stores messages based on game conditions.

- 🖥 DOM elements: Used to update the UI dynamically.

### 🔄 Functions:

- 🎲 getRandomCard(): Returns a random card value (1–11, with face cards being 10 and Ace being 11).

- 🏁 startGame(): Initializes the game by drawing two cards and calculating their sum.

- 📊 renderGame(): Updates the UI with the drawn cards, sum, and game messages.

- 🎴 newCard(): Draws an additional card if the player is still in the game and hasn’t won.
