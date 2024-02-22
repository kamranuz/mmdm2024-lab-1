# HSE MMDM 2024 | Lab Work №1

## Rules:
- Grade calculation: 0.3*Task1 + 0.3*Task2 + 0.4*Task3
- Small group work: 1-3 students
- Basic solution of each task = 8 points; Creativity and visualization can earn 9 or 10 points
- Write original code for algorithms
- Deadline: TBD
## Team:
- [Mike Shklyar](https://t.me/MC_Mikel)
- [Вацлав Соколовский](https://t.me/RinokuS)
- [Kamron Abdulkhaev](https://t.me/kamran_uz)

## Task 1:
Utilize genetic algorithm to find the global extremum of given functions for n-dimensional objective functions.

(a) Maximize 

$$
f(x, y) =
3(1-x)^2 * exp(-x^2-(y+1)^2) - 10(x/5 - x^3 - y^5) * exp(-x^2-y^2) - 1/3 * exp(-(x+1)^2-y^2)
$$

(b) Minimize 
$$
f(x, y) =
-0.0001 * (|sin(x) * sin(y) * exp(|100 - sqrt(x^2 + y^2)/π|) + 1)^0.1,
\quad
(x, y) in [-10, 10]^2
$$

## Task 2:
Determine the Pareto front for a multi-objective optimization problem using the NSGA II algorithm. Consider n = 3, but experimentation with other values is encouraged.

Minimize 
$$
f(x) = { f_1(x) = 1 - exp(-Σ(x_i - √(1/n))^2), f_2(x) = 1 - exp(-Σ(x_i + √(1/n))^2) }, \quad
-4 ≤ x_i ≤ 4, 1 ≤ i ≤ n
$$

## Task 2:
TBD
