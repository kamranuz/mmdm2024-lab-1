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


(a) Minimize

$$
\max_{x,y} f(x, y)=3(1-x)^2\exp\left(-x^2-(y+1)^2\right)-10\left(\frac{x}{5} - x^3 - y^5\right)
\exp\left(-x^2-y^2\right)-\frac{1}{3} \exp\left(-(x+1)^2-y^2\right)
$$

(b) Minimize

$$
\min_{x,y} f(x, y)=-0.0001\left(
    \left\lvert
        \sin(x)
        \sin(y)
        \exp\left(\left|
            100 - \frac{\sqrt{x^2 + y^2}}{\pi}
            \right|\right)
    \right\rvert
    +
    1
\right)^{0.1}
\quad
(x, y) \in [-10, 10]^2
$$

## Task 2:
Determine the Pareto front for a multi-objective optimization problem using the NSGA II algorithm. Consider n = 3, but experimentation with other values is encouraged.

Minimize 

$$
\min_{x} = \begin{cases}f_1(x)=1-\exp\left(    -\sum_{i=1}^{n}        \left(            x_i - \sqrt{\frac{1}{n}}        \right)^2    \right) f_2(x)=1-\exp\left(    -\sum_{i=1}^{n}        \left(            x_i + \sqrt{\frac{1}{n}}        \right)^2    \right)\end{cases}\quad-4 \leq x_i \leq 4, \quad 1 \leq i \leq n
$$

## Task 2:
TBD
