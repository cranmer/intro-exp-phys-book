# From Error to uncertainty

## The meaning of statistical uncertainty [~Ch 4 & 5]

Three ways to discuss statistical uncertainty

   1. The true mean and standard deviation from a distribution f(x) are unknown to the experimenter that doesn’t know true underlying distribution -- Sec [5.2]

        * The variance (standard deviation squared) and mean are defined by integrals 
        \begin{equation}
        \sigma^2 \equiv \int (x-\mu)^2 f(x) dx
        \end{equation}
        where
        \begin{equation}
        \mu \equiv \int x f(x) dx
        \end{equation}
        * This is our goal.

   2. The estimate of standard deviation from a repeated observations $\{x_i\}$ -- [Sec. 4.2]
    * The observations are “samples” from the true distribution $f(x)$
    * A histogram of the $\{x_i\}$ is an approximation of the distribution $f(x)$
    * The “sample mean” and “sample variance” are estimates of the true mean and variance defined by sums

        \begin{equation}
        \sigma^2_n \equiv \frac{1}{n-1}\sum_{i=1}^n (x_i-\bar{x})^2 
        \end{equation}
        where
        \begin{equation}
        \bar{x} \equiv \frac{1}{n}\sum_{i=1}^n x_i 
        \end{equation}

    * The ”n-1” is so that the estimate of the variance is unbiased. Using 1/n is biased.
    * This is the best we can do as experimentalists from data without additional assumptions.


   3. The estimate of uncertainty in a single observation: eg. $x \pm \delta x$ -- [Sec 4.3]
    * This is what you typically do in a lab. There is no equation, this is where you have to use your judgement
    * Your goal is that $\delta x$ is close to $\sigma$
    * The meaning is that if you were to repeat the measurements several times (and nothing else changed), the values you observe would spread around the true, unknown value. The size of this spread is our statistical uncertainty.