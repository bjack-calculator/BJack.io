# BJack.io — Blackjack Calculator

**BJack.io** is a blackjack calculator for **expected value (EV), blackjack odds, basic strategy, card counting and real-time shoe tracking**.

Unlike a static blackjack strategy chart, BJack calculates decisions using the **actual cards remaining in the shoe**. Enter cards as they appear, and the calculator updates the shoe composition, probabilities, count and expected value.

👉 **[Open BJack.io](https://bjack.io/)**

## Features

### 🧮 Blackjack EV & Strategy Calculator

Calculate the expected value of the available actions:

- Hit
- Stand
- Double
- Split
- Surrender

BJack compares the mathematical value of each option based on the current hand, table rules and remaining shoe.

👉 **[Blackjack Strategy Calculator](https://bjack.io/blackjack-strategy-calculator)**

### 🃏 Real Shoe Tracking

Track the cards that have already been dealt and calculate probabilities from the **remaining shoe**.

Card entry supports:

- **All 52** — full card selection
- **Rank → suit** — select rank and suit
- **Rank only** — faster card entry

### 📊 1–8 Decks

Configure the number of decks used at the table:

**1 · 2 · 4 · 6 · 8 decks**

The selected deck count affects probabilities, true count, EV and strategy calculations.

👉 **[Blackjack Basic Strategy Chart](https://bjack.io/blackjack-basic-strategy-chart)**

### 📈 Six Card Counting Systems

BJack supports multiple blackjack counting systems:

- **Hi-Lo**
- **KO (Knock-Out)**
- **Zen Count**
- **Omega II**
- **Wong Halves**
- **Red 7**

The calculator tracks the **running count** and, where applicable, calculates the **true count** based on the remaining decks.

👉 **[Blackjack Card Counting Guide](https://bjack.io/blog/how-to-count-cards-blackjack)**

### 🎯 Basic Strategy & Deviations

BJack provides basic strategy based on the selected rules and can account for changes in the actual shoe composition.

Supported table parameters include:

- H17 / S17
- Double rules
- Double After Split (DAS)
- Surrender
- Resplitting
- Split-ace rules
- 3:2 / 6:5 blackjack payout
- 1–8 decks

### 🎲 Blackjack Odds & Probabilities

The calculator can determine dealer and player probabilities, including:

- Dealer 17–21
- Dealer bust
- Player bust
- Win / push / loss probabilities
- Insurance EV
- Expected value of available actions

## How It Works

```text
Table Rules
    ↓
Cards Already Seen
    ↓
Remaining Shoe
    ↓
Counting System
    ↓
Dealer & Player Probabilities
    ↓
Action EV + Current Count
