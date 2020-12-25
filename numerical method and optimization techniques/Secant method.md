# Secant method

 - Find points x0 and x1 such that x0 < x1 and f(x0)*f(x1)<0

 - Take the interval [x0,x1] and find next value
        x2 = x0 - f(x0).(x1 - x0)/(f(x1)-f(x0))

 - If f(x2)=0 => x2 is an exact root

 - Else : x0 = x1 and x1 = x2

Repeat the procedure until convergence is obtained.
