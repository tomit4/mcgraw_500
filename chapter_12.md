# Chapter 12 Sequences, Series, and Probability

---

## Sequences

---

**For questions 457-459,** write the first four terms of the sequence whose
general term is given.

---

**457.** $n - 3$

**Answer:**

$$ a_1 = (1) - 3 = -2 $$

$$ a_2 = (2) - 3 = -1 $$

$$ a_3 = (3) - 3 = 0 $$

$$ a_4 = (4) - 3 = 1 $$

$$ \boxed{\left\{-2, -1, 0, 1\right\}} $$

---

**458.** $\dfrac{1}{4^{n - 2}+ 1}$

**Answer:**

$$ a_1 = \frac{1}{4^{1 - 2} + 1} = \frac{1}{4^{-1} + 1} = \frac{1}{\dfrac{1}{4} + 1} = \frac{1}{\dfrac{5}{4}} = \frac{4}{5} $$

$$ a_2 = \frac{1}{4^{2 - 2} + 1} = \frac{1}{4^0 + 1} = \frac{1}{2} $$

$$ a_3 = \frac{1}{4^{3 - 2} + 1} = \frac{1}{4^{1} + 1} = \frac{1}{4 + 1} = \frac{1}{5} $$

$$ a_4 = \frac{1}{4^{4 - 2} + 1} = \frac{1}{4^{2} + 1} = \frac{1}{16 + 1} = \frac{1}{17} $$

$$ \boxed{\left\{\frac{4}{5}, \frac{1}{2}, \frac{1}{5}, \frac{1}{17}\right\}} $$

---

**459.** $\dfrac{(-1)^n}{n + 2}$

**Answer:**

$$ a_1 = \frac{(-1)^1}{1 + 2} = -\frac{1}{3} $$

$$ a_2 = \frac{(-1)^2}{2 + 2} = \frac{1}{4} $$

$$ a_3 = \frac{(-1)^3}{3 + 2} = -\frac{1}{5} $$

$$ a_4 = \frac{(-1)^4}{4 + 2} = \frac{1}{6} $$

$$ \boxed{\left\{-\frac{1}{3}, \frac{1}{4}, -\frac{1}{5}, \frac{1}{6}\right\}} $$

---

**460.** Find the general term.

$$ \frac{1}{2}, \frac{3}{4}, \frac{5}{6} , \frac{7}{8}, \dots $$

**Answer:**

$$ \boxed{\frac{2n - 1}{2n}} $$

---

**461.** Find the first four terms of the sequence defined recursively by the
given equations.

$$ A_1 = 1, A_2 = 1, A_{n + 2} = A_n + A_{n + 1} $$

**Answer:**

Taken from back of book.

This is the famous
[Fibonacci Sequence](https://en.wikipedia.org/wiki/Fibonacci_sequence). The
terms are simply adding up the previous term to get the next one:

$$ \boxed{1, 1, 2, 3} $$

---

**462.** Define the given sequence by using a recursive formula.

$$ 1, 1, 5, 17, 61, \dots $$

**Answer:**

Taken from back of book.

$$ a_{n + 2} = 3a_{n + 1} + 2a_n $$

---

## Series

---

**463.** Expand

$$ \sum^{3}_{i = 1}(-1)^{i + 1}(x^i - 1) $$

**Answer:**

$$ i = 1 \text{: } (-1)^{1 + 1}(x^1 - 1) = (-1)^2(x - 1) = 1(x - 1) = x - 1 $$

$$ i = 2 \text{: } (-1)^{2 + 1}(x^2 - 1) = (-1)^3(x^2 - 1) = -1(x^2 - 1) = -x^2 + 1 $$

$$ i = 3 \text{: } (-1)^{3 + 1}(x^3 - 1) = (-1)^4(x^3 - 1) = 1(x^3 - 1) = x^3 - 1 $$

$$ (x - 1) + (-x^2 + 1) + (x^3 - 1) = x^3 - 1 -x^2 + 1 + x - 1 = x^3 - x^2 + x - 1  $$

$$ \boxed{\sum^{3}_{i = 1}(-1)^{i + 1}(x^i - 1) = x^3 - x^2 + x - 1} $$

---

**464.** Write the given series, using summation (sigma) notation.

$$ 1 - 3 + 5 - 7 + 9 - 11 $$

**Answer:**

Taken from back of book.

$$ \sum^{6}_{i = 1}(-1)^{i + 1}(2i - 1) $$

---

## Arithmetic and Geometric Sequences

---

**For questions 465 and 466,** tell whether the given sequence is arithmetic or
geometric.

---

**465.**

$$ 1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \dots $$

**Answer:**

This sequence just halves the previous number in the sequence, multiplying it by
$\dfrac{1}{2}$ every iteration. Thusly it is a _geometric_ sequence.

---

**466.**

$$ 10, 6, 2, -2, -6, \dots $$

**Answer:**

This sequence subtracts $4$ every iteration, and is thusly an _arithmetic_
sequence.

---

**467.** Find all indicated quantities, where $a_1, a_2, \dots, a_n, \dots$ is
an arithmetic sequence, $d = \text{common difference}$, and
$S = \text{sum of first } n \text{terms of the sequence}$.

$$ a_1 = 1, a_2 = 5, S_{21} = \text{ ?} $$

**Answer:**

We can solve this using the Arithmetic Sequence Sum Formula:

$$ \sum^{n}_{k = 1}\left[a_1 + (k - 1)d\right] = \frac{n}{2}(a_1 + a_n) $$

If we consider that we can take the difference, multiply it by the last index,
and add it to the first term, we'll get the last term in the sequence:

$$ a_n = a_1 + (n - 1)d $$

We have a value for $a_n$ that can be represented in terms of $a_1$ and $n$.

Since $S_n$ is the sum formula, we can substitute $S_n$ for the sigma notation.
Additionally, the sum formula can be further evaluated by substituting out $a_n$
for our evaluated representation from above:

$$ S_n = \frac{n}{2}\left[a_1 + \left(a_1 + (n - 1)d\right)\right] $$

And simplified, we get:

$$ S_n = \left(\frac{n}{2}\right)[2a_1 + (n - 1)d] $$

From here, we can plug in our final index, $21$, and get our summation:

$$ S_{21} = \left(\frac{21}{2}\right)[2(1) + (21 - 1)(4)] $$

$$ S_{21} = \left(\frac{21}{2}\right)[2 + (20)(4)] $$

$$ S_{21} = \left(\frac{21}{2}\right)[2 + 80] $$

$$ S_{21} = \left(\frac{21}{2}\right)[82] $$

$$ \boxed{S_{21} = 861} $$

---

**468.** Find the sum of the first eight terms of the Sequence

$$ 1, \frac{1}{3}, \frac{1}{9}, \frac{1}{27}, \dots $$

, the sequence is geometric, and $r$ stands for the common ratio.

**Answer:**

The standard geometric sum formula reads as follows:

$$ \sum^{n}_{k = 1}{a_1r^{k - 1}} = \frac{a_1}{1 - r}\left(1 - r^n\right) $$

We know that the sequence's ratio is $\dfrac{1}{3}$ just from looking at it
closely. We also know that we're only summing up the first $8$ terms. We can
therefore fill in our geometric sum formula as follows:

$$ \sum^{8}_{k = 1}{1\left(\frac{1}{3}\right)^{1 - 1}} = \frac{1}{1 - \left(\dfrac{1}{3}\right)}\left(1 - \left(\frac{1}{3}\right)^8\right) $$

$$ \sum^{8}_{k = 1}1 = \frac{1}{1 - \left(\dfrac{1}{3}\right)}\left(1 - \left(\frac{1}{3}\right)^8\right) $$

$$ \sum^{8}_{k = 1}1 = \frac{3}{2}\left(1 - \frac{1}{6561}\right) $$

$$ \sum^{8}_{k = 1}1 = \frac{3}{2}\left(1 - \frac{1}{6561}\right) $$

$$ \sum^{8}_{k = 1}1 = \frac{3}{2}\left(\frac{6560}{6561}\right) $$

$$ \sum^{8}_{k = 1}1 = \frac{19680}{13122} $$

---

## Geometric Series

---

**469.** Write the given geometric series, using sigma (summation) notation.

$$ 2 + 1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots $$

**Answer:**

The standard geometric sum formula reads as follows:

$$ \sum^{n}_{i = 1}{a_1r^{i - 1}} $$

We an see that $r = \dfrac{1}{2}$, and in this case since it goes on forever,
$n = \infty$. And honestly that's all we need to write this out in sigma
notation:

$$ \boxed{\sum^{\infty}_{i = 1}{2\left(\frac{1}{2}\right)^{i - 1}}} $$

---

**For questions 470-473,** find the sum or show that the series has no sum.

---

**470.**

$$ 1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots $$

**Answer:**

Recall that the full geometric series sum formula reads as:

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{a_1}{1 - r}\left(1 - r^n\right) $$

We get a finite sum if $|r| < 1$, and we get an Infinite sum (no sum) if
$|r| \geq 1$.

And this case, our $r = \dfrac{1}{2}$, so we will have a finite sum. Note that
we replace $r^n$ with $0$, as when $|r| < 1$, this means we have a fraction that
simply gets infinitely smaller the closer we get to $\infty$.

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{1}{1 - \left(\dfrac{1}{2}\right)}\left(1 - 0\right) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{1}{\dfrac{1}{2}}(1) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = 2(1) $$

$$ \boxed{\sum^{\infty}_{k = 1}{a_1r^{k - 1}} = 2} $$

---

**471.**

$$ 1 + \frac{1}{9} + \frac{1}{81} + \dots $$

**Answer:**

$$ r = \frac{1}{9} $$

$$ |r| < 1 $$

So we will have a finite sum.

$$ \sum^{\infty}_{k = 1}{a_1\left(\frac{1}{9}\right)^{k - 1}} = \frac{1}{1 - \left(\dfrac{1}{9}\right)}\left(1 - 0\right) $$

$$ \sum^{\infty}_{k = 1}{a_1\left(\frac{1}{9}\right)^{k - 1}} = \frac{1}{\left(\dfrac{8}{9}\right)}(1) $$

$$ \boxed{\sum^{\infty}_{k = 1}{a_1\left(\frac{1}{9}\right)^{k - 1}} = \frac{9}{8}} $$

---

**472.**

$$ 3 + 6 + 12 + 24 + \dots $$

**Answer:**

$$ r = 2 $$

Because $|r| \geq 1$, we know that this series _Diverges_, and therefore is an
Infinite series with no finite sum:

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{a_1}{1 - r}\left(1 - r^n\right) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{3}{1 - 2}\left(1 - 2^{\infty}\right) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{3}{-1}\left(1 - \infty\right) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = -3\left(1 - \infty\right) $$

And this is as far as we can really evaluate, this series doesn't exist.

---

**473.**

$$ 3 - \frac{3}{2} + \frac{3}{4} - \frac{3}{8} + \dots $$

**Answer:**

$$ r = -\frac{1}{2} $$

$$ |r| < 1 $$

This series will _converge_, and thusly we will have a finite sum:

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{a_1}{1 - r}\left(1 - r^n\right) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{3}{1 - \left(-\dfrac{1}{2}\right)}\left(1 - 0\right) $$

$$ \sum^{\infty}_{k = 1}{a_1r^{k - 1}} = \frac{3}{\left(\dfrac{3}{2}\right)}(1) $$

$$ \boxed{\sum^{\infty}_{k = 1}{a_1r^{k - 1}} = 2} $$

---

## Binomial Theorem

**For questions 474-476,** expand the given expression, using the binomial
theorem.

---

**474.** $(x + y)^2$
