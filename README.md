# Sudoku solver

It’s pretty straightforward to make a Sudoku solver in Prolog when applying CLP ([Constraint Logic Programming](https://en.wikipedia.org/wiki/Constraint_logic_programming)).

Open `sudoku.pl` in your favorite Prolog environment and type:

`solve_sudoku.`

Then you can enter the known numbers one by one.

```
+-+-+-+-+-+-+
|9 8| 5 |  7|
|72 |1
```

When complete, the program determines and prints the solution.

```
+-+-+-+-+-+-+
|938|254|617|
|726|193|854|
|514|876|329|
+-+-+-+-+-+-+
|692|387|145|
|187|465|293|
|453|921|768|
+-+-+-+-+-+-+
|345|712|986|
|871|649|532|
|269|538|471|
+-+-+-+-+-+-+
```

