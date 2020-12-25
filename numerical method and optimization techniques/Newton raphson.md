# Newton Raphson method

 - Find points a and b such that a<b and f(a).f(b)<0
 - Take the interval [a,b] and find the value x0 = (a+b)/2
 - Find f(x0) and f'(x0)
 - Find x1 : 
        x1 = x0 - (f(x0)/f'(x0))
 - If f(x0) = 0 => x1 is an exact root
 - Else x0 = x1

 Repeat the procedure until f(xi) = 0.
