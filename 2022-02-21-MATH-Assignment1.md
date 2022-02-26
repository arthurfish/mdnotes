Discrete mathematics- Assignment 1

1. $r \land \sim v$
2. table is below:

| p | q | r | A |
|---|---|---|---|
| F | F | F | T |
| F | F | T | T |
| F | T | F | F |
| F | T | T | T |
| T | F | F | T |
| T | F | T | T |
| T | T | F | F |

3. let *p* = "The car is out of gas", and let *q* = "The fuel line is plugged"
   Then statement is $p \lor q$, negation of the statement is $\sim (p \lor q) = \sim p \land \sim q$, Which is **"The car is not out of gas and the fuel line isn't plugged"**

4. From De morgan's law, answer is $x < 3 or x > 5 or |x - y| \geq 1$
5. Not equal.
$$
\begin{aligned}

\sim (\sim p \lor q) &=& p \land \sim q \\\\
p \land (p \land \sim q) \; &=&  p \land p \land \sim q \\
&=& (p \land p) \land \sim q \\
&=& p \land \sim q \\\\
(p \land \sim q) \lor (p \land q) &=& p \land (\sim q \lor q) \\
&=& p \land True \\
&=& p
\end{aligned}
$$

6. Truth table is as below:

| A | B | $(A \implies B)$ | $(\neg A \implies \neg B)$ |
|---|---|-----------------|---------------------------|
| F | F | T               | T                         |
| F | T | T               | T                         |
| T | F | F               | F                         |
| T | T | T               | T                         |
    So They are equal

7. $(\neg B \land A) = False$ Can be translated as $\neg (\neg B \land A)$, which can be replaced by $(B \lor \neg A)$ by De Morgan's law, then it is $\neg A \lor  B$, which is same as $(A \implies B)$

8. As follow:
$$
\begin{aligned}
(A \implies B) &=& \neg A \lor B \\
&=& \neg (X \lor Y \lor Z) \lor B \\ \\
(X \implies B) \land (Y \implies B) \land (Z \implies B)
&=& (\neg X \lor B) \land (\neg Y \lor B) \land (\neg Z \lor B) \\
&=& (B \lor (\neg X \land \neg Y)) \land (B \lor \neg Z) \\
&=& B \lor (\neg X \land \neg Y \land \neg Z) \\
&=& B \lor \neg(X \land Y \land Z) \\
&=& (A \implies B)
\end{aligned}
$$

9. .
$$
\begin{aligned}

(p \land q) \lor (\neg p \lor (p \land \neg q)) \\
&=& (p \land q) \lor \neg(\neg(\neg p \lor (p \land \neg q)))\\
&=& (p \land q) \lor \neg(p \land \neg(p \land q))\\
&=& (p \land q) \lor \neg(p \land (\neg p \lor q))\\
&=& (p \land q) \lor \neg((p \land \neg p) \lor (p \land q))\\
&=& (p \land q) \lor \neg(p\land q)\\
&=& True\\
\end{aligned}
$$