This mod significantly slows down late game tech progression in G&K. The early game is unaffected.

Wonder costs are similarly adjusted to prevent the tech leader from constructing all of them.

The chart shows tech and wonder costs by era.

<img width="605" height="544" alt="image" src="https://github.com/user-attachments/assets/97ad2085-bfae-41ea-88c0-a422f82fe818" />

The impact is noticable from the Medieval / Renaissance era.

The formula used is `NEW_TECH_COST = G&K_TECH_COST * (1 + 1 / 750) ^ (ERA_NUMBER ^ 2.5)`, rounded to two significant digits.
