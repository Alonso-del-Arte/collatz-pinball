# Collatz Pinball

WORK IN PROGRESS

The player will launch the pinball up to some pseudorandom positive integer, 
then try to steer the ball towards a larger power of 2 in the hopes of coming 
down to 1 very quickly by operating flippers that will be provided on numbers of 
the form $6k + 4$. I haven't worked out the scoring yet.

The Collatz function $f(n)$ is defined as $f(n) = 3n + 1$ if $n$ is odd, 
$f(n) = \frac{n}{2}$ if $n$ is even. The function is iterated, with successive 
results becoming input for the function all over again. As long as $n$ is 
positive, the iterations will reach a power of 2 and soon settle on the cycle 4, 
2, 1. Or so goes the theory anyway. At4 least this has been confirmed for numbers 
way larger than the ones we'll be dealing with in this game.

For example, if we start with 144, iterating the Collatz function gives us the 
sequence 144, 72, 36, 18, 9, 28, 14, 7, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 
5, 16, 8, 4, 2, 1, 4, 2, 1, 4, 2, 1, ...

Then in this game, if the initial launch put the ball at 144, (FINISH WRITING)
