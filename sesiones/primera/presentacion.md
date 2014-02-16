# DP (aka Programación Dinámica)

> I thought dynamic programming was a good name. It was something not even a Congressman could object to. So I used it as an umbrella for my activitie. <cite>Richard Bellman to describe the process of solving problems where one needs to find the best decisions one after another</cite>


# Existen dos formas de DP

## Top-down

This is the direct fall-out of the recursive formulation of any problem. If the solution to any problem can be formulated recursively using the solution to its subproblems, and if its subproblems are overlapping, then one can easily memoize or store the solutions to the subproblems in a table. Whenever we attempt to solve a new subproblem, we first check the table to see if it is already solved. If a solution has been recorded, we can use it directly, otherwise we solve the subproblem and add its solution to the table.


## Bottom-up

Once we formulate the solution to a problem recursively as in terms of its subproblems, we can try reformulating the problem in a bottom-up fashion: try solving the subproblems first and use their solutions to build-on and arrive at solutions to bigger subproblems. This is also usually done in a tabular form by iteratively generating solutions to bigger and bigger subproblems by using the solutions to small subproblems. For example, if we already know the values of F41 and F40, we can directly calculate the value of F42.

# Ejemplo

Recomendación de Jorman http://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=279&page=show_problem&problem=3928
