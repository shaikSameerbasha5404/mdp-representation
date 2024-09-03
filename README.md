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

![sam1](https://github.com/user-attachments/assets/6d3a6bb7-2d76-4081-8f13-2a76d30e5efb)


## PYTHON REPRESENTATION:
~~~
NAME : Shaik Sameer Basha
REG NO : 212222240093

P = {
    0:{
        0: [(0.44,0,0,True),(0.13,1,0,False)],
        1: [(0.13,1,0,False),(0.44,0,0,True)]
    },
    1:{
        0: [(0.44,1,0,False),(0.13,2,1,True)],
        1: [(0.13,2,1,True),(0.44,1,0,False)]
    },
    2:{
        0: [(0.44,2,1,True),(0.13,1,1,False)],
        1: [(0.13,1,1,False),(0.44,2,1,True)]
    }
}


~~~

## OUTPUT:

![sam2](https://github.com/user-attachments/assets/725e4898-cebf-44c2-8e04-dd276d5fc4c6)



## RESULT:
Therefore an MDP representation has been created for a real world scenario with all the states, actions and rewards.
