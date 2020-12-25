# Bisection method

For any continuous function f(x)

 - Find two points **a** and **b** such that **a<b** and **f(a)*f(b) < 0**

 - Find the **midpoint of a and b**- t

 - If f(t) = 0
    - t is the root of the function

 - Else :
    - If f(t)* f(**b**) < 0 -> **a** = t
    - If f(t)* f(**a**) < 0 -> **b** = t

Repeat last three steps until f(t)=0
