# Demonstration of the simplex algorithm

A pedagogical tool for running the simplex algorithm.

![image](https://github.com/playwithalgos/simplex/assets/43071857/87e66e58-2157-497a-bf97-b5cd061f2c8f)


## Features

- simple to use. You even do not have to click on a button "Execute"!
- it shows the polyhedron of the solution space in 2D and 3D. With more dimensions, it shows a projection.
- input in text form for instance:
   ````
   max 2x + 3y
    x <= 1
    2x + 6y <= 1
   ````

   ```
   max x + 6y + 13z
   x <= 200
   y <= 300
   x+y+z <= 400
   y+3z <= 600
   ```

- you can use (almost) any names for variable as long it starts with a letter ;)

  ````
   max 2chocolate + 3milk
    chocolate <= 1
    2chocolate + 6milk <= 1
   ````

  also works!

- only maximization problem in canonical form
