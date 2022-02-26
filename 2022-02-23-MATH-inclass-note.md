p77

23 .
let p = "Oleg is a math major"
let q = "Oleg is an economics major"
let r = "Oleg is required to take Math 362"

$$
p \lor q \\
p \implies r \\
\therefore q \lor \sim r
$$

| p | q | r | p V q | p => r |  p V ~r | Critical? |
|---|---|---|-------|--------|---------|-----------|
| 0 | 0 | 0 | 0     | 1      | 1       |           |
| 0 | 0 | 1 | 0     | 1      | 0       |           |
| 0 | 1 | 0 | 1     | 1      | 1       | valid     |
| 0 | 1 | 1 | 1     | 1      | 0       | no valid  |
| 1 | 0 | 0 | 1     | 0      | 1       |           |
| 1 | 0 | 1 | 1     | 1      | 1       | valid     |
| 1 | 1 | 0 | 1     | 0      | 1       |           |
| 1 | 1 | 1 | 1     | 1      | 1       | valid     |

28,
let p = "number of rational number equals irrational numbers"

let q = "set of all irrational numbers is infinite"

$$
p \implies q \\
q \\
\therefore p
$$

| p | q | p -> q | q | p | Critical? |
|---|---|--------|---|---|-----------|
| 0 | 0 | 1      | 0 | 0 |           |
| 0 | 1 | 1      | 1 | 0 | invalid   |
| 1 | 0 | 0      | 0 | 1 |           |
| 1 | 1 | 1      | 1 | 1 | valid     |