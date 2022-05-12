# game_or_xr_dev

Artificial Intelligence in Game
===

NPCs with a certain distance will follow/attack towards the Player,

Materials around the Player can get closer to the Player,

Develop AI by applying Case-based reasoning (CBR), which is a process to solve new problems based on previous solutions that have similarities.

CBR: generate hypotheses about new situations based on their past experiences to learn new skills.

CBR does not require a training process that requires a large training dataset.

Decision making can utilize Rule-Based Systems (RBS),

RBS used to store and manipulate knowledge to interpret information in useful ways.

[comment]: # (https://github.com/khoir335/game_or_xr_dev/blob/abc9610851fa4438fcf956d761f88e8bc2e1e524/images/images1a.png)

[comment]: # (Figure 1.1 A diagram of case based reasoning in France)

![alt text](https://github.com/khoir335/game_or_xr_dev/blob/abc9610851fa4438fcf956d761f88e8bc2e1e524/images/images2a.png)

Figure 1. Case-Based reasoning general model.

1.	__Retrieve__: Given a target problem, retrieve cases relevant to solving it from memory. A case consists of a problem, its solution, and, typically, annotations about how the solution was derived. For example, suppose Fred wants to prepare blueberry pancakes. Being a novice cook, the most relevant experience he can recall is one in which he successfully made plain pancakes. The procedure he followed for making the plain pancakes, together with justifications for decisions made along the way, constitutes Fred's retrieved case.

2.	__Reuse__: Map the solution from the previous case to the target problem. This may involve adapting the solution as needed to fit the new situation. In the pancake example, Fred must adapt his retrieved solution to include the addition of blueberries.

3.	__Revise__: Having mapped the previous solution to the target situation, test the new solution in the real world (or a simulation) and, if necessary, revise. Suppose Fred adapted his pancake solution by adding blueberries to the batter. After mixing, he discovers that the batter has turned blue – an undesired effect. This suggests the following revision: delay the addition of blueberries until after the batter has been ladled into the pan.

4.	__Retain__: After the solution has been successfully adapted to the target problem, store the resulting experience as a new case in memory. Fred, accordingly, records his new-found procedure for making blueberry pancakes, thereby enriching his set of stored experiences, and better preparing him for future pancake-making demands.

Transfer Learning?
