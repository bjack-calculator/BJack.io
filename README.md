# BJack.io — Blackjack Calculator

**BJack.io** is a blackjack calculator for **expected value (EV), blackjack odds, basic strategy, card counting and real-time shoe tracking**.

Unlike a static blackjack strategy chart, BJack calculates decisions using the **actual cards remaining in the shoe**. Enter cards as they appear, and the calculator updates the shoe composition, probabilities, count and expected value.

## Features

### Blackjack EV & Strategy Calculator

Calculate the **expected value (EV)** of every available blackjack action — **Hit, Stand, Double, Split and Surrender**. BJack compares each option using the current hand, table rules and remaining shoe composition.

 [**Blackjack Strategy Calculator**](https://bjack.io/blackjack-strategy-calculator)

### Real Shoe Tracking

Track cards as they are dealt and calculate probabilities from the **actual remaining shoe**. Cards can be entered using **All 52**, **Rank → Suit**, or **Rank Only** modes, depending on the level of detail required.

### 1–8 Decks

Configure **1, 2, 4, 6 or 8 decks**. The selected number of decks affects the remaining-card probabilities, true count, EV and strategy calculations.

 [**Blackjack Basic Strategy Chart**](https://bjack.io/blackjack-basic-strategy-chart)

### Card Counting Systems

BJack supports **six blackjack counting systems**: **Hi-Lo, KO (Knock-Out), Zen Count, Omega II, Wong Halves and Red 7**. The calculator tracks the **running count** and, where applicable, calculates the **true count** based on the decks remaining.

👉 [**Blackjack Card Counting Guide**](https://bjack.io/blog/how-to-count-cards-blackjack)

### Basic Strategy & Deviations

Generate blackjack basic strategy based on the selected table rules and current shoe composition. Supported rules include **H17 / S17, Double, Double After Split (DAS), Surrender, Resplitting, Split Aces, 3:2 / 6:5 blackjack payouts and 1–8 decks**.

### Blackjack Odds & Probabilities

Calculate **dealer and player probabilities**, including dealer **17–21 and bust**, player bust probability, **win / push / loss probabilities, insurance EV** and the expected value of available actions.

## How It Works

BJack combines the **current hand, table rules, cards already seen, remaining shoe and counting system** to calculate blackjack probabilities and expected value.

```text
Table Rules + Cards Seen + Remaining Shoe + Counting System
                           ↓
              Probabilities & Card Count
                           ↓
                  EV for Each Action
