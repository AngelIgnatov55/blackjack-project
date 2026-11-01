\# Blackjack: Simulation and Strategy Comparison



A Python project that simulates thousands of blackjack games and compares simple strategies for the player.



\## Question

Does it matter at which hand value the player stops drawing cards? We compare the thresholds 13, 15 and 17 by their win rate.



\## Contents of the notebook

1\. Deck of cards and the value of a hand (an ace counts as 11 or 1)

2\. A function that plays one game: player against dealer

3\. Simulation of 10,000 games per strategy and the win rate $\\hat{p} = W / N$

4\. A bar chart of the results

5\. Standard error and 95% confidence intervals of the win rates

6\. Conclusion and references



\## How to run

1\. Install Jupyter and `matplotlib`.

2\. Open `blackjack.ipynb` in Jupyter.

3\. Run all cells (Run -> Run All Cells). The simulation takes a few seconds.



\## Results

All strategies win about 40-42% of the games. The thresholds 13 and 15 look slightly better than 17, but the confidence intervals partly overlap, so the difference is not clearly established with 10,000 games per strategy.



\## Simplifications

One player against the dealer, no splitting, doubling or insurance, no special payout for a natural 21, and a freshly shuffled 52-card deck for every game. The dealer draws until reaching at least 17.



\## Sources

See the References section at the end of the notebook.

