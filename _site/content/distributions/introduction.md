# Distributions

When measuring a continuous quantity x the probability to get exactly a specific value of x is usually 0. Instead, one asks what is the probability to get x in some range.
The probability to find x in the range [x,x+dx] is f(x) dx, where f(x) is called a probability density function, or “distribution” for short.
Normalization
The probability that one obtains x in the full range must be one, so we have the
normalization condition Z
f(x)dx = 1
Change of variables
If we change variables from x to y(x) then we should have P(a<x<b) = P(y(a) < y < y(b)). If we call the distributions f(x) and g(y), then we can write these two probabilities as integrals
 Z b
Z y(b)
f(x)dx =
by change of variables, we can re-write the integral on the right-hand side as
Z b
f(x)dx =
a
Histograms
Z b a
,thus
f(x) = g(y) dx 
   .
a
d y g(y(x))dxdx
y(a)
g(y)dy 


## Histograms

Repeated observations {xi} = {x1, ...., xn} can be thought of as “samples” from the distribution f(x). A common way to estimate the true, underlying parent distribution for these samples is the histogram. One defines ranges of x, called “bins”, and counts how many of the samples fall in each bin.
A normalized histogram is formed by dividing each of the bin counts by the total number of samples. This way, the sum of the normalized histogram bins is 1. Due to the properties of the Poisson distribution (below), an estimate for the uncertainty in the bin is 1/√ n .

## Gaussian (or Normal) Distribution [Ch 5.3]

The most common distribution we encounter is the Gaussian or Normal distribution. It is characterized (or parametrized) by two quantities: the mean μ and standard deviation σ. The probability density function is given by the following equation:
G(x|μ,  ) = p 1 e 2⇡ 
 
(x μ)2 2 2
  To help remember this, think of a parabola centered at μ. You can use dimensional analysis to remember that it is σ2 in the denominator of the exponential. Also remember that if σ is smaller the distribution is narrower, so it must also be taller for the normalization integral to be 1. The minus sign in the exponential is easy to remember, because if x is far from μ, then the probability must be very small.
Notice, that the probability density can be larger than 1 ,for example G(0|0, 1/2π) > 1.

## Poisson Distribution [Ch 11]

The Poisson distribution describes the probability to have n events occur when μ are expected. For example, if one expects μ =3.14 decays of a radioactive particle in one day, it gives the probability to observe n=0,1,2,3,4,.... decays in a day. Note, this is not a probability density because n is discrete.
μn e μ
Poisp(n|μ) =
 =μ n ̄=μ
μ and σ=√μ. Notice that the relative uncertainty drops like: σ/μ ~ 1/√μ .

## Binomial Distribution [Ch 10]
The binomial distribution describes the probability to have exactly k successes given n independent trials, when p is the probability of success for a single trial. The first part of the equation is a “combinatorial factor” that describes for all the ways one can have k successes. When n is much larger than k it is approximately a Poisson distribution.
PAGE 2 OF 7
PROF. KYLE CRANMER
Binomial(k|n,p)=
n! k n k
  (k)=np(1 p)
p (1 p) k=np


