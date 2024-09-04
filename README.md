# MDP REPRESENTATION

## AIM:
The representation of real world scenario using Markov Decision Process by stating all the states,actions and environment with respective rewards.

## PROBLEM STATEMENT:
To develop a game which will promote to other level,when the agent complete its task correctly.
### Problem Description
If the agent unable to complete the given task,then there is no promotion to other level,when it reaches the final level,it will recieve a reward.

### State Space
{L1,L2,L3}--->{0,1,2}
### Sample State
L1--->{0}

### Action Space
Moving Left(1)

Stay in the same level(0)

### Sample Action
Stay in the same level(0)

### Reward Function
+1(When it reaches the goal state or final level)

### Graphical Representation

![RL-1](https://github.com/user-attachments/assets/7715a6c6-a583-4229-8ead-1382c528c8b3)


## PYTHON REPRESENTATION:
~~~
NAME : Shaik Sameer Basha
REG NO : 212222240093

solve_mdp={
0: { 1: [(0.4,1,0,False),(0.5,0,0,False),(0.1,2,0,False)], 0: [(0.6,0,0,False),(0.3,2,0,False),(0.1,3,1,True)] },
1: { 1: [(0.5,2,0,False),(0.4,0,0,False),(0.1,3,1,True)], 0: [(0.6,0,0,False),(0.4,2,0,False)] },
2: { 1: [(0.6,3,1,True),(0.4,1,0,False)], 0: [(0.6,1,0,False),(0.4,3,1,True)] },
3: { 1: [(0.6,3,1,True),(0.2,2,0,False),(0.2,0,0,False)], 0: [(0.5,1,0,False),(0.3,3,1,True),(0.2,2,0,False)] }
}
~~~

## OUTPUT:


![RL Ex-1](https://github.com/user-attachments/assets/7eb5c1e9-0522-40f1-aed4-41a3c5e0b382)


## RESULT:
Therefore an MDP representation has been created for a real world scenario with all the states, actions and rewards.
