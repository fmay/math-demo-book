Most of the more “interesting” functions for finding critical points aren’t polynomials however.  So let’s take a look at some functions that require a little more effort on our part.

||| important
**Example 2**
Determine all the critical points for the function.

$ g(t)=\sqrt[3]{t^2}(2t-1) $

|||

**Solution**
To find the derivative it’s probably easiest to do a little simplification before we actually differentiate.  Let’s multiply the root through the parenthesis and simplify as much as possible.  This will allow us to avoid using the product rule when taking the derivative.

$g(t)=t^\frac{2}{3}(2t-1)=2t^\frac{5}{3}-t^\frac{2}{3} $

Now differentiate.

$g^\prime(t)=\frac{10}{3}t^\frac{2}{3}-\frac{10t^\frac{2}{3}}{3}-\frac{2}{3t^\frac{1}{3}}$

We will need to be careful with this problem.  When faced with a negative exponent it is often best to eliminate the minus sign in the exponent as we did above.  This isn’t really required but it can make our life easier on occasion if we do that. 

 
Notice as well that eliminating the negative exponent in the second term allows us to correctly identify why  $t=0$ is a critical point for this function.  Once we move the second term to the denominator we can clearly see that the derivative doesn’t exist at $t=0$ and so this will be a critical point.  If you don’t get rid of the negative exponent in the second term many people will incorrectly state that $t=0$ is a critical point because the derivative is zero at t=0.  

While this may seem like a silly point, after all in each case $t=0$ is identified as a critical point, it is sometimes important to know why a point is a critical point.  In fact, in a couple of sections we’ll see a fact that only works for critical points in which the derivative is zero.

 
So, we’ve found one critical point (where the derivative doesn’t exist), but we now need to determine where the derivative is zero (provided it is of course…).  To help with this it’s usually best to combine the two terms into a single rational expression.  So, getting a common denominator and combining gives us,

$g^\prime(t)=\frac{10t-2}{3t^\frac{1}{3}}$

Notice that we still have $t=0$ as a critical point.  Doing this kind of combining should never lose critical points, it’s only being done to help us find them.  As we can see it’s now become much easier to quickly determine where the derivative will be zero.  Recall that a rational expression will only be zero if its numerator is zero (and provided the denominator isn’t also zero at that point of course).

So, in this case we can see that the numerator will be zero if $t=\frac{1}{5}and so there are two critical points for this function.

$t=0$ and $t=\frac{1}{5} $
