# Coding-Assignment-for-ORIE-4350-Introduction-to-Game-Theory

This repository contains my work for a project wherein I simulated ficticious play in two Rock-Paper-Scissor games, with a different payoff matrix for each game, and compared the results to learn about strategy and payoff convergence, and also cyclic nature in strategies and payoffs. 

This is the premis: 

Simulate fictitious play in game 1 and game 2, respectively. You can choose an arbi-
trary initial state for your algorithm. In each game, answer the following questions:

1. Does strategy sequence converge? Does strategy sequence converge in time averaged sense?
2. Does payoffs converge?
3. Have you detected cycles in strategies and payoffs?

Game 1:

     R       P       S
R (0, 0) (-1, 1) (1, -1)
P (1, -1) (0, 0) (-1, 1)
S (-1, 1) (1, -1) (0, 0)


Game 2:
     R     P      S
R (0, 0) (0, 1) (1, 0)
P (1, 0) (0, 0) (0, 1)
S (0, 1) (1, 0) (0, 0)
