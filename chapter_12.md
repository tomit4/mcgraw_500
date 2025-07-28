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

**Answer:**

We did not cover the Binomial Theorem in Professor Leonard's Lecture series, but
here is a [CueMath Article](https://www.cuemath.com/algebra/binomial-theorem/)
on the subject. In summary, one can ascertain the binomial theorem by the
following sum formula:

$$ (a + b)^n = \sum^{n}_{k = 0}\binom{n}{k}a^{n - k}b^k $$

Or also:

$$ (a + b)^n = \sum^{n}_{k = 0}\binom{n}{k}a^{k}b^{n - k} $$

It is often used when you need to expand an expression $(x + y)^n$ where $n$ is
too large to easily distribute.

Note that:

$$ \binom{n}{k} = \frac{n!}{k!(n - k)!} $$

Is the **binomial coefficient**, also read as "n choose k".

Also note that in the above summation:

- $a, b$ are any real (or complex) numbers

- $n$ is a **non-negative integer**

- $k$ ranges from $0$ to $n$

Let's now exemplify by solving this simple expression:

$$ (x + y)^2 $$

$$ (x + y)^2 = \sum^{2}_{k = 0}\binom{2}{k}x^{2 - k}y^k = \binom{2}{0}x^2 + \binom{2}{1}xy + \binom{2}{2}y^2 $$

Where $k$ is the bottom numbers of the binomial coefficient, $0, 1, 2$
respectively.

Let's write in the factorial so it is more clear what's happening:

$$ (x + y)^2 = \sum^{2}_{k = 0}\left(\frac{n!}{k!(n - k)!}\right)x^{2 - k}y^k = \left(\frac{2!}{0!(2 - 0)!}\right)x^2 + \left(\frac{2!}{1!(2 - 1)!}\right)xy + \left(\frac{2!}{2!(2 - 2)!}\right)y^2 $$

Because we haven't worked with factorials in a very long time, let's make a
brief note that $0! = 1$, and $0! \neq 0$. This is because we can always count
**nothing** from a set exactly $1$ time.

This evaluates to:

$$ (x + y)^2 = \sum^{2}_{k = 0}\left(\frac{n!}{k!(n - k)}\right)x^{2 - k}y^k = 1x^2 + 2xy + 1y^2 $$

And we get our final answer:

$$ (x + y)^2 = \sum^{2}_{k = 0}\binom{2}{k}x^{2 - k}y^k = \binom{2}{0}x^2 + \binom{2}{1}xy + \binom{2}{2}y^2 = x^2 + 2xy + y^2 $$

---

**475.** $(2a + 3)^5$

**Answer:**

$$ (2a + 3)^5 = \sum^{5}_{k = 0}\binom{5}{k}(2a)^{5 - k}3^k = \binom{5}{0}(2a)^53^0 + \binom{5}{1}(2a)^43^1 + \binom{5}{2}(2a)^33^2 + \binom{5}{3}(2a)^23^3 + \binom{5}{4}(2a)^13^4 + \binom{5}{5}(2a)^03^5 $$

We won't bother writing the binomial coefficients in its factorial form, but
simply evaluate each term like so:

$$ \left(\frac{n!}{k!(n - k)!}\right) $$

$$ (2a + 3)^5 = \sum^{5}_{k = 0}\binom{5}{k}(2a)^{5 - k}3^k = 1(32)a^5(1) + 5(16)a^4(3) + 10(8)a^3(9) + 10(4)a^2(27) + 5(2)a^1(81) + 1(1)(1)(243) $$

$$ (2a + 3)^5 = \sum^{5}_{k = 0}\binom{5}{k}(2a)^{5 - k}3^k = 32a^5 + 240a^4 + 720a^3 + 1080a^2 + 810a + 243 $$

---

**476.** $(2x - 4)^3$

**Answer:**

$$ (2x - 4)^3 = \sum^{3}_{k = 0}\binom{3}{k}(2x)^{3 - k}(-4)^k = \binom{3}{0}(2x)^3(-4)^0 + \binom{3}{1}(2x)^2(-4)^1 + \binom{3}{2}(2x)^1(-4)^2 + \binom{3}{3}(2x)^0(-4)^3 $$

$$ (2x - 4)^3 = \sum^{3}_{k = 0}\binom{3}{k}(2x)^{3 - k}(-4)^k = (1)(8)x^3(1) + 3(4)x^2(-4) + 3(2)x(16) + 1(1)(1)(-64) $$

$$ (2x - 4)^3 = \sum^{3}_{k = 0}\binom{3}{k}(2x)^{3 - k}(-4)^k = 8x^3 - 48x^2 + 96x - 64 $$

---

## Permutations, Combinations, and Probability

---

**For questions 477-479,** calculate the given permutation or combination.

---

**477.** $P(7, 1)$

**Answer:**

This is a "$7$ choose $1$" permutation:

$$ {}^nP_r = \frac{n!}{(n - r)!} $$

$$ {}^7P_1 = \frac{7!}{(7 - 1)!} $$

$$ {}^7P_1 = \frac{7!}{6!} $$

$$ \boxed{{}^7P_1 = 7} $$

---

**478.** $P(4, 1) + P(4, 2) + P(4, 3) + P(4, 4)$

**Answer:**

$$ \frac{4!}{(4 - 1)!} + \frac{4!}{(4 - 2)!} + \frac{4!}{(4 - 3)!} + \frac{4!}{(4 - 4)!} $$

$$ \frac{4!}{3!} + \frac{4!}{2!} + \frac{4!}{1!} + \frac{4!}{0!} $$

$$ \boxedd{{}^4P_1 + {}^4P_2 + {}^4P_3 + ()^4P_4 = 64} $$

---

**479.** $C(31, 2)$

**Answer:**

$$ {}^nC_r = \frac{n!}{(n - r)!(r!)} $$

$$ {}^31C_2 = \frac{31!}{(31 - 2)!(2!)} $$

$$ \boxed{{}^31C_2 = 465} $$

---

**480.** How many three-digit numbers can be formed with the digits
$1, 2, 3, 4, 5$ ?

(A) if repetitions are allowed

**Answer:**

If no repetitions are allowed, then a different Permutation formula is used:

$$ n^r $$

$$ 5^3 $$

$$ \boxed{125} $$

(B) if no repetitions are allowed

**Answer:**

If no repetitions are allowed, then the standard Permutation formula is used:

$$ {}^nP_r = \frac{n!}{(n - r)!} $$

$$ {}^5P_3 = \frac{5!}{(5 - 3)!} $$

$$ {}^5P_3 = \frac{5!}{2!} $$

$$ \boxed{{}^5P_3 = 60} $$

---

**481.** How many committees, consisting of $1$ first-year student, $1$
sophomore, and $1$ junior can be selected from $40$ first-year students, $30$
sophomores, and $25$ juniors?

**Answer:**

This problem appears to be like a Permutation or Combination, but is actually
simply a matter of applying the Fundamental Counting Principle, also known as
the [Rule of Product](https://en.wikipedia.org/wiki/Rule_of_product).

If you are only ever choosing $1$ from a series of groups, and you need to know
how many subgroups you can create from those choices, then you can simply
multiply the total of each group together to get your answer:

$$ \boxed{40 \cdot 30 \cdot 25 = 30000} $$

---

**482.** Five boys are in a room that has $4$ doors. In how many ways can they
leave the room?

**Answer:**

Each boy has four choices. This is a simple permutation problem, where we can
simply take the number of doors and raise it to the power of the number of boys
to find our answer:

$$ 4^5 = 4 \cdot 4 \cdot 4 \cdot 4 \cdot 4 $$

$$ \boxed{4^5 = 1024} $$

---

**483.** How many even numbers of three digits can be made with the digits
$1, 2, 3, 4, 5, 6, 7$ if no digit is repeated?

**Answer:**

The even numbers are $2, 4, 6$, and this must sit in our _ones_ place.

If we choose $2$:

We are left with the set:

$$ \left\{1, 3, 4, 5, 6, 7\right\} $$

After we choose our _ones_: We are left with $6$ digits.

After We choose any of these to be our _hundreds_ place: We are left with $5$
digits.

With our _ones_ already chosen, we multiply our remaining digits after we choose
our _ones_ by our remaining digits after we choose our _hundreds_:

$$ 6 \cdot 5 = 30 $$

Because we do this now for $4$, and $6$, and we end up with the same amount of
other two digit combinations to create our three digit number, we get:

$$ (6 \cdot 5) + (6 \cdot 5) + (6 \cdot 5) = \boxed{90} $$

---

**484.** Seven songs are to be given in a program. In how many different orders
could they be rendered?

**Answer:**

$$ \boxed{7! = 5040} $$

---

**485.** Find the number of permutations that can be formed by using all the
given letters.

$$ \text{ALABAMA} $$

**Answer:**

$$ \frac{7!}{4!} = \boxed{210} $$

---

**486.** A line is formed by $5$ girls and $5$ boys, with boys and girls
alternating. Find the number of ways of making the line.

**Answer:**

$$ GBGBGBGBGB $$

$$ BGBGBGBGBG $$

There are only $2$ formations to this line. Each time one of the boys or girls
lines up, there is one less than the remainder left. This is two factorials
multiplied together then.

$$ 2(5! \cdot 5!) = 28800 $$

---

**487.** Do as in question 486, but with circular arrangement.

**Answer:**

Since the boys and girls are lining up in a circle, there is no beginning or
end, and thusly we can simply take our answer from 486, and divide it by the
total number of boys and girls ($10$):

$$ \frac{28800}{10} = \boxed{2880} $$

---

**488.** Show that $P(n, n - 1) = P(n, n)$

$$ {}^nP_r = \frac{n!}{(n - r)!} $$

$$ {}^nP_{n - 1} = \frac{n!}{(n - (n - 1))!} $$

$$ {}^nP_{n - 1} = \frac{n!}{(n - n + 1)!} $$

$$ {}^nP_{n - 1} = \frac{n!}{1!} $$

$$ 1! = 1 $$

$$ {}^nP_{n - 1} = \frac{n!}{1} $$

$$ {}^nP_{n - 1} = n! $$

$$ {}^nP_{n} = \frac{n!}{(n - n)!} $$

$$ {}^nP_{n} = \frac{n!}{0!} $$

$$ 0! = 1 $$

$$ {}^nP_{n} = \frac{n!}{1} $$

$$ {}^nP_{n} = n! $$

$$ {}^nP_{n - 1} = {}^nP_{n} $$

---

**489.** In how many different ways can a tennis team of $4$ be chosen from $17$
players?

**Answer:**

This is a combination.

$$ {}^nC_r = \frac{n!}{(n - r)!(r!)} $$

$$ {}^{17}C_4 = \frac{17!}{(17 - 4)!(4!)} $$

$$ \boxed{{}^{17}C_4 = 2380} $$

---

**490.** Nine points, no three of which are on a straight line, are marked on a
chalkboard. How many lines, each through two of the points, can be drawn?

This is a simple combination of $2$ chosen from $9$:

$$ {}^nC_r = \frac{n!}{(n - r)!(r!)} $$

$$ {}^9C_2 = \frac{9!}{(9 - 2)!(2!)} $$

$$ \boxed{{}^9C_2 = 36} $$

---

**491.** Seven different coins are tossed simultaneously. In how many ways can
$3$ heads and $4$ tails come up?

**Answer:**

This is two different combinations multiplied together:

$$ {}^7C_3 \cdot {}^4C_4 $$

Where first $3$ different ways of coming up heads are come up with from the full
set of $7$ coins, and then $4$ different ways of coming up from the remaining
$4$ coins.

$$ {}^7C_3 = \frac{7!}{(7 - 3)!(3!)} $$

$$ {}^7C_3 = 35 $$

$$ {}^4C_4 = \frac{4!}{(4 - 4)!(4!)} $$

$$ {}^4C_4 = 1 $$

$$ {}^7C_3 \cdot {}^4C_4 = 35 \cdot 1  $$

$$ \boxed{{}^7C_3 \cdot {}^4C_4 = 35} $$

Note that we could also have done:

$$ {}^7C_4 \cdot {}^3C_3 $$

And gotten the same answer.

---

**492.** In how many ways can a court of $9$ judges make a $5$-to-$4$ decision?

**Answer:**

This is actually quite similar in the way we solve it to 491:

$$ {}^9C_5 \cdot {}^4C_4 $$

$$ {}^9C_5 = \frac{9!}{(9 - 5)!(5!)} $$

$$ {}^9C_5 = 126 $$

$$ {}^4C_4 = \frac{4!}{(4 - 4)!(4!)} $$

$$ {}^4C_4 = 1 $$

$$ {}^9C_5 \cdot {}^4C_4 = 126 \cdot 1 $$

$$ \boxed{{}^9C_5 \cdot {}^4C_4 = 126} $$

---

**493.** Four delegates are to be chosen from $8$ members of a club.

(A) How many choices are possible?

**Answer:**

$$ {}^8C_4 = \frac{8!}{(8 - 4)!(4!)} $$

$$ \boxed{{}^8C_4 = 70} $$

(B) How many choices contain member $A$?

**Answer:**

This is the same as choosing $3$ from a group of $7$, as we are simply ensuring
$1$ member from the original $8$ is definitely in the club.

$$ {}^7C_3 = \frac{7!}{(7 - 3)!(3!)} $$

$$ \boxed{{}^7C_3 = 35} $$

\(C\) How many choices contain $A$ and $B$?

**Answer:**

This is the same as choosing 2 from a group of $6$ since the original $2$ are
ensured to be in the group.

$$ {}^6C_2 = \frac{6!}{(6 - 2)!(2!)} $$

$$ \boxed{{}^6C_2 = 15} $$

---

**494.** The alphabet consists of $21$ consonants and $5$ vowels. In how many
ways can $5$ consonants and $3$ vowels be selected?

**Answer:**

We can multiple the combination of the 5 consonants in 21 total consonants and
the 3 vowels in the total 5 vowels:

$$ {}^{21}C_5 \cdot {}^5C_3 $$

$$ {}^{21}C_5 = \frac{21!}{(21 - 5)!(5!)} $$

$$ {}^{21}C_5 = 20349 $$

$$ {}^5C_3 = \frac{5!}{(5 - 3)!(3!)} $$

$$ {}^5C_3 = 10 $$

$$ {}^{21}C_5 \cdot {}^5C_3 = 20349 \cdot 10 $$

$$ \boxed{{}^{21}C_5 \cdot {}^5C_3 = 203490} $$

---

**495.** A ball is chosen from a bag containing $2$ white, $1$ black,$ and $2$
red balls.

(A) Find the probability that a white ball is chosen.

**Answer:**

The basic probability formula is:

$$ P(E) = \frac{S}{n} $$

Where $E$ is an event, $S$ is the number of ways the event can occur, and $n$ is
the total number of possibilities.

Thusly if we are calculating the probability of a white ball being chosen. we
can plug in:

$$ P(W) = \frac{2}{2 + 1 + 2} $$

$$ \boxed{P(W) = \frac{2}{5}} $$

(B) Find the probability that a black ball is chosen.

**Answer:**

$$ \boxed{P(B) = \frac{1}{5}} $$

\(C\) Find the probability of choosing a green ball.

**Answer:**

There are $0$ green balls.

$$ P(G) = \frac{0}{5} $$

$$ \boxed{P(G) = 0} $$

---

**496.** Three pennies are tossed at the same time.

(A) Find the probability that all $3$ land on heads ($H$).

**Answer:**

Every time a penny is tossed, it can only have either $H$ or $T$ (tails), thusly
the probability that all three will turn up $H$ can be calculated like so:

$$ P(H) \cdot P(H) \cdot P(H) = 2 \cdot 2 \cdot 2 = 2^3 = 8 $$

$$ \boxed{P(H, H, H) = 8} $$

(B) Find the probability that $2$ are $H$ and $1$ is $T$ (tails).

**Answer:**

There are $8$ possibilities altogether. For tails to show up on a single coin,
we can calculate that as a combination:

$$ P(T) = {}^3C_1 = \frac{3!}{(3 - 1)!(1!)} $$

$$ P(T) = {}^3C_1 = 3 $$

And there simply is this combination divided by the total number of
possibilities that we will get $(H, H, T)$:

$$ \boxed{P(H, H, T) = \frac{3}{8}} $$

\(C\) Find the probability that $1$ is $H$ and $2$ are $T$.

**Answer:**

This is the same as 496B, as the chances for one coin being Heads is the same
combination formula:

$$ P(H) = {}^3C_1 = \frac{3!}{(3 - 1)!(1!)} $$

$$ P(H) = {}^3C_1 = 3 $$

And there simply is this combination divided by the total number of
possibilities that we will get $(H, T, T)$:

$$ \boxed{P(H, T, T) = \frac{3}{8}} $$

---

**497.** Three balls are drawn from a bag containing $6$ red and $5$ black
balls.

(A) Find the probability that all are red.

**Answer:**

We are looking for:

$$ P(R, R, R) $$

The total number of possibilities for any combination of $3$ balls are:

$$ {}^{11}C_3 = \frac{11!}{(11 - 3)(3!)} $$

$$ {}^{11}C_3 = 165 $$

And since there are $6$ red balls, there is ${}^6C_3$ possible ways to draw all
$3$ red balls:

$$ {}^6C_3 = \frac{6!}{(6 - 3)!(3!)} $$

$$ {}^6C_3 = 20 $$

Wen can then find our answer by dividing this by the total number of possible
choices:

$$ P(R, R, R) = \frac{{}^{6}C_3}{{}^{11}C_3} $$

$$ P(R, R, R) = \frac{20}{165} $$

$$ \boxed{P(R, R, R) = \frac{4}{33}} $$

(B) Find the probability that all are black.

**Answer:**

Same kind of idea as above, but we don't have to calculate ${}^11C_3$ since we
already have it for the total possible combinations.

For black however:

$$ {}^5C_3 = \frac{5!}{(5 - 3)!(3!)} $$

$$ {}^5C_3 = 10 $$

$$ P(B, B, B) = \frac{{}^5C_3}{{}^{11}C_3} $$

$$ P(B, B, B) = \frac{10}{165} $$

$$ \boxed{P(B, B, B) = \frac{2}{33}} $$

\(C\) Find the probability of $2$ being red and $1$ being black.

**Answer:**

This requires a bit more thinking. But not much. We just have to calculate both
the odds of drawing $2$ red balls, and the odds of drawing $1$ red ball and
multiply those odds together.

The odds of drawing $2$ red balls are:

$$ {}^6C_2 = \frac{6!}{(6 - 2)!(2!)} $$

$$ {}^6C_2 = 15 $$

$$ P(R, R) = \frac{{}^6C_2}{{}^{11}C_3} $$

$$ P(R, R) = \frac{15}{165} $$

$$ P(R, R) = \frac{1}{11} $$

And the odds of drawing $1$ black ball are:

$$ {}^5C_1 = \frac{5!}{(5 - 1)!(1!)} $$

$$ {}^5C_1 = 5 $$

$$ P(B) = \frac{{}^5C_1}{{}^{11}C_3} $$

$$ P(B) = \frac{5}{165} $$

$$ P(B) = \frac{1}{33} $$

We now can simply multiply these results to find our answer:

$$ P(R, R, B) = \frac{{}^6C_2{}^5C_1}{{}^{11}C_3} $$

$$ P(R, R, B) = \frac{15(5)}{165} $$

$$ \boxed{P(R, R, B) = \frac{5}{11}} $$

---

**498.** One card is picked from an ordinary $52$-card deck.

(A) Find the probability that a red card is chosen.

**Answer:**

There are $26$ cards that are red and $26$ that are black.

$$ \boxed{P(R) = \frac{26}{52} = \frac{1}{2}} $$

(B) Find the probability that a queen is chosen.

**Answer:**

There are $4$ queens in the whole deck.

$$ \boxed{P(Q) = \frac{4}{52} = \frac{1}{13}} $$

\(C\) Find the probability that a red $8$ is chosen.

**Answer:**

There are $2$ red $8$'s in the deck:

$$ \boxed{P(\text{red } 8) = \frac{2}{52} = \frac{1}{26}} $$

---

**499.** The probability that a brush salesperson will make a sale at one house
is $\dfrac{2}{3}$ and at a second house is $\dfrac{1}{2}$.

(A) Find the probability the sales person will make both sales.

**Answer:**

Simply multiply the probabilities together:

$$ \boxed{\frac{2}{3} \cdot \frac{1}{2} = \frac{1}{3}} $$

(B) Find the probability he or she will make neither sale.

**Answer:**

The chances of not making the sale at the first house is $\dfrac{1}{3}$, and the
chance of not making the sale at the second house is $\dfrac{1}{2}$:

$$ \boxed{\frac{1}{3} \cdot \frac{1}{2} = \frac{1}{6}} $$

\(C\) Find the probability she or he will make at least one sale.

**Answer:**

They will either make a sale on the first house but not the second, or they will
make a sale on the second house but not hte first, or they will make a sale on
both houses:

$$ P(S, N) + P(N, S) + P(S, S) $$

The chances of her making both sales is actually the same as if she made neither
sale:

$$ P(N, N) = P(S, S) = \frac{1}{6} $$

And we know that the chances of selling one but not the other is:

$$ P(N, S) = P(S, N) = \frac{1}{3} $$

Thusly we can calculate our chance of making at least one sale with the
following:

$$ P(S, N) + P(N, S) + P(S, S) = \frac{1}{3} + \frac{1}{3} + \frac{1}{6} $$

$$ \boxed{P(S, N) + P(N, S) + P(S, S) = \frac{5}{6}} $$

(D) Find the probability the salesperson will make _exactly_ one sale.

**Answer:**

This is just:

$$ P(S, N) + P(N, S) $$

$$ P(S, N) + P(N, S) = \frac{1}{3} + \frac{1}{3} $$

$$ \boxed{P(S, N) + P(N, S) = \frac{2}{3}} $$

---

**500.** Bag $1$ contains $2$ white balls and $1$ red ball; bag $2$ contains $3$
white balls and $1$ red ball. A bag is chosen at random, and a ball is picked at
random. What is the given probability?

(A) The ball chosen is red.

**Answer:**

The chance of choosing bag $1$ is $\dfrac{1}{2}$.

THe chance of choosing a red ball from bag $1$ is $\dfrac{1}{3}$.

The chance of choosing bag $2$ is $\dfrac{1}{2}$.

The chance of choosing a red ball from bag $2$ is $\dfrac{1}{4}$.

$$ P(R) = \left[P(B_1) \cdot P(B_1 \text{ and } R)\right] + \left[P(B_2) \cdot P(B_2 \text{ and } R)\right] $$

$$ P(R) = \left(\frac{1}{2} \cdot \frac{1}{3}\right) + \left(\frac{1}{2} \cdot \frac{1}{4}\right) $$

$$ \boxed{P(R) = \frac{7}{24}} $$

(B) The ball chosen is white.

**Answer:**

The chance of choosing bag $1$ is $\dfrac{1}{2}$.

THe chance of choosing a white ball from bag $1$ is $\dfrac{2}{3}$.

The chance of choosing bag $2$ is $\dfrac{1}{2}$.

The chance of choosing a red ball from bag $2$ is $\dfrac{3}{4}$.

$$ P(W) = \left[P(B_1) \cdot P(B_1 \text{ and } W)\right] + \left[P(B_2) \cdot P(B_2 \text{ and } W)\right] $$

$$ P(W) = \left(\frac{1}{2} \cdot \frac{2}{3}\right) + \left(\frac{1}{2} \cdot \frac{3}{4}\right) $$

$$ \boxed{P(W) = \frac{17}{14}} $$
