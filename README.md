# Assignment 1: Pole Balancing Cart
<img src="Reference/PoleBalancingCart.png"/>

## Problem Definition
Given the instance of the cart pole environment, how to develop Reinforcement Learning Agent in making decision to balance the pole optimally?

## About

This is a project for SC3000 which focuses on developing Machine Learning Agent to make optimal action in different situations. For detailed walkthrough, please view the file in "Assignment 1" folder in order from:

1. [23S2 SC30000_CZ3005 Lab Assignment 1] <br> Problem Description, Requirements & Guidelines. More details in the doc file.<br><br>
2. [Sc3000_Lab1.ipynb]<br>Implemented Q-learning Reinforcement Learning Algorithm in Python to enable AI agent to make informed decisions from interactive learning with environment. As the hyperparameters play an important factors in our agent development, all parameters in Q-Learning Algorithm such as learning rate, discount factor and epsilon value to achieve average cumulative rewards of 500.00 ( Maximum cut-off point).To further improve our agent's informed decision making process, the Penalty Function is devised in penalizing undesirable actions, guiding agent towards more stable and optimal behaviours. Finally, we conducted rigorous evaluation, testing and training to validate and improve the agent's effectiveness and robustness.
<br><br>

### Datasets Folder
Contains two saved dataset upon finetuning our model.

1. Bin_1.npy - All possible states( Cart Position, Cart Velocity, Pole Angle, Pole Angular Velocity)
2. QTable_1.npy - Collection of Q(s, pi) values, where pi is the optimal policy and s is the state.

## Libraries

- Gym
- NumPy
- Pandas
- Matplotlib

## What did we learn from this project?

- Implemented Q-Learning Algorithm using Epsilon-Greedy Q-Learning Algorithm to update Q-Value, Q(s,a)
- Implemented Penalty Function to punish undesireble action.
- Rigorous Training and effectively finetuned parameters (epsilon value, episodes, learning rate etc) to achieve maximum output score

# Assignment 2: Prolog Programming
<img src="Reference/PrologLogo.png"/>

## Problem Definition
Use Prolog Programming in First Order Logic

## About

This is a project for SC3000 which focuses on developing First Order Logic Induction using Prolog Programming in determining Rivalry Relationship, Royal Family Succession Line.

1. [A33_qn_1_2/rivalry.pl] <br> Given knowledgebase of competitors, product ownership, company ownership etc relationship, deduce if a company owner is unethical and stole competitor's product. <br><br>
2. [A33_qn_2_1/royalFamily1.pl]<br> Given knowledgebase of royalties sibling, parent relationship and royalties identity, deduce the succession line based on gender.
<br><br>
3. [A33_qn_2_2/royalFamily2.pl]<br> Given knowledgebase of royalties sibling, parent relationship and royalties identity, deduce the succession line based on age.
<br><br>

## What did we learn from this project?

- Introduction to Prolog Programming.
- Exercise First Order Logic in facts deduction and induction.

## Contributors

- @dotalim0204 (Lim Jun Hern, U2120981B) 
- @HLeong12345 (Leong Hong Yi, U2120932C) 
- @Jabezng2 (Jabez Ng Yong Xin, U2120757D) 
