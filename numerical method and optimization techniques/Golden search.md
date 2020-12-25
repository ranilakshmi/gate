# Golden search method

 - To determine the minimizer of a function f:R->R over a closed interval [a,b].
 - Assume that the function is unimodal which means that it has only one local minimizer.

## Algorithm

 - We have to choose two intermediate points a1 and b1 in such a way that the reduction in the range is symmetric.

        a1 - a0 = b0 - b1 = p(b0 - a0)


    - If f(a1) < f(b1),minimizer must lie in the interval [a0,b1]

            b2 = a1

            Find a2 and repeat the process.

    - If f(a1) >= f(b1),minimizer is located in the range [a1,b0]

            a2 = b1

            Find b2 and repeat the process.

 - The uncertainity range is reduced by the ratio 1-p = (0.61803) at every stage.Hence N steps of reduction using the golden search method reduces the range by the factor (1-p)^N = (0.61803)^N.
