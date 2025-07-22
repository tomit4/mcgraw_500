# Chapter 10 Conic Sections

---

## The Circle

---

**For questions 402-404,** find the center and radius of the given circle.

---

**402.** $x^2 + y^2 = 100$

**Answer:**

The standard circle formula can be written as:

$$ (x - h)^2 + (y - k)^2 = r^2 $$

Where the center is at $(h, k)$, and $r$ represents the radius.

Thusly in this case, our center is:

$$ \boxed{(0, 0)} $$

And our radius is $\sqrt{100}$, and therefore:

$$ \boxed{r = 10} $$

---

**403.** $7x^2 + 7y^2 + 14x - 56y - 25 = 0$

**Answer:**

Here we have to combine our like terms:

$$ (7x^2 + 14x) + (7y^2 - 56y) = 25  $$

$$ 7(x^2 + 2x) + 7(y^2 - 8y) = 25 $$

Now we have to complete the square for our two variadic terms to get it into
standard form:

$$ 7(x^2 + 2x + 1) + 7(y^2 - 8y + 16) = 25 + 7(1) + 7(16) $$

$$ 7(x + 1)^2 + 7(y - 4)^2 = 144$$

We can now divide out $7$ from both sides:

$$ (x + 1)^2 + (y - 4)^2 = \frac{144}{7} $$

And lo and behold, we are in standard form, albeit with an awkward fraction for
our squared radius. Nevertheless, from here we can easily determine the center
and the radius:

The center is:

$$ \boxed{(-1, 4)} $$

And the radius is:

$$ r = \sqrt{\frac{144}{7}} $$

$$ r = \frac{12}{\sqrt{7}} $$

Let's rationalize that denominator:

$$ \boxed{r = \frac{12\sqrt{7}}{7}} $$

---

**404.** $x^2 + y^2 - 6x + 8y - 11 = 0$

**Answer:**

This is similar to 403. Let's first try and get this into standard form by
grouping our like terms and then completing the square:

$$ (x^2 - 6x) + (y^2 + 8y) = 11 $$

Again, completing the square can take the middle term, divided by $2$ and then
squaring it to find our $c$ term:

$$ c = \left(\frac{b}{2}\right)^2 $$

So let's do that for each term now (remember to add any new numbers to the other
side of the equation):

$$ (x^2 - 6x + 9) + (y^2 + 8y + 16) = 11 + 9 + 16 $$

$$ (x - 3)^2 + (y + 4)^2 = 36 $$

And we're in standard form, from here we can determine the center of the circle
as:

$$ \boxed{(3, -4)} $$

And the radius as:

$$ r = \sqrt{36} $$

$$ \boxed{r = 6} $$

---

**405.** Write the equation of a circle with center $(-2, -3)$ and radius
$\sqrt{7}$.

**Answer:**

This is relatively straight forward, recall that the formula for a standard
circle is:

$$ (x - h)^2 + (y - k)^2 = r^2 $$

In this case, we can just plug in our given center point and radius from the
problem statement (just be careful with signs):

$$ (x - (-2))^2 + (y - (-3))^2 = (\sqrt{7})^2 $$

And let's just clean up the signs and simplify a bit to get our final answer:

$$ \boxed{(x + 2)^2 + (y + 3)^2 = 7} $$

---

**406.** Find the center and radius of the circle passing through the given
points.

$(0, 0) \text{, } (1, 1) \text{, } (1, 2)$

**Answer:**

The process to find the center and radius is lengthy, but pretty easily
understood. All we have to do is plug in at least two of these points into the
circle formula for the values of $x$ and $y$ and then solve for the unknown $h$
and $k$, and $r$ values to find the center:

$$ (x - h)^2 + (y - k)^2 = r^2 $$

$$ (1 - h)^2 + (2 - k)^2 = r^2 $$

$$ (1 - h)(1 - h) + (2 - k)(2 - k) = r^2 $$

$$ 1 - 2h + h^2 + 4 - 4k + k^2 = r^2 $$

And now let's plug in another point:

$$ (1 - h)^2 + (1 - k)^2 = r^2 $$

$$ (1 - h)(1 - h) + (1 - k)(1 - k) = r^2 $$

$$ 1 - 2h + h^2 + 1 - 2k + k^2 = r^2 $$

Even though this is somewhat haphazard looking, we can actually set these two
equal to each other:

$$ 1 - 2h + h^2 + 4 - 4k + k^2 = 1 - 2h + h^2 + 1 - 2k + k^2 $$

Now let's simplify, and see if we can solve for any variable (if not, we just
set one side to $0$, and go further down the rabbit hole):

$$ \cancel{1} \cancel{- 2h} \cancel{+ h^2} + 4 - 4k \cancel{+ k^2} = \cancel{1} \cancel{- 2h} + \cancel{h^2} + 1 - 2k \cancel{+ k^2} $$

$$ 4 - 4k = 1 - 2k $$

$$ 3 = 2k $$

$$ k = \frac{3}{2} $$

It makes sense that $h$ would cancel because both points being plugged in,
$(1, 1)$ and $(1, 2)$ have the same $x$ value. Therefore to solve for $h$, we'll
have to explore $(0, 0)$ with the value for $k$ plugged in:

$$ (0 - h)^2 + (0 - k)^2 = r^2 $$

$$ (0 - h)^2 + \left(0 - \frac{3}{2}\right)^2 = r^2 $$

$$ (-h)^2 + \left(-\frac{3}{2}\right)^2 = r^2 $$

$$ h^2 + \frac{9}{4} = r^2 $$

We can now set this equal to one of our previous evaluations with our found
value for $k$ plugged in to solve for $h$:

$$ h^2 + \frac{9}{4} = 1 - 2h + h^2 + 1 - 2\left(\frac{3}{2}\right) + \left(\frac{3}{2}\right)^2 $$

$$ h^2 + \frac{9}{4} = 1 - 2h + h^2 + 1 - \frac{6}{2} + \frac{9}{4} $$

$$ \cancel{h^2} \cancel{+ \frac{9}{4}} = 1 - 2h \cancel{+ h^2} + 1 - 3 \cancel{+ \frac{9}{4}} $$

$$ 1 - 2h + 1 - 3 = 0 $$

$$ -2h + 2 - 3 = 0 $$

$$ -2h - 1 = 0 $$

$$ -2h = 1 $$

$$ h = -\frac{1}{2} $$

And now we can solve for $r$ using any of our given points. Firstly, again,
recall our circle formula:

$$ (x - h)^2 + (y - k)^2 = r^2 $$

Now let's just plug in our values, being aware of signs:

$$ \left(x - \left(-\frac{1}{2}\right)\right)^2 + \left(y - \left(\frac{3}{2}\right)\right)^2 = r^2 $$

$$ \left(x + \frac{1}{2}\right)^2 + \left(y - \frac{3}{2}\right)^2 = r^2 $$

And now we can plug in any point and solve for $r$:

$$ \left(0 + \frac{1}{2}\right)^2 + \left(0 - \frac{3}{2}\right)^2 = r^2 $$

$$ \left(\frac{1}{2}\right)^2 + \left(-\frac{3}{2}\right)^2 = r^2 $$

$$ \frac{1}{4} + \frac{9}{4} = r^2 $$

$$ \frac{10}{4} = r^2 $$

$$ \frac{5}{2} = r^2 $$

$$ r = \sqrt{\frac{5}{2}} $$

And we can rationalize the denominator:

$$ r = \frac{\sqrt{5}}{\sqrt{2}} \cdot \frac{\sqrt{2}}{\sqrt{2}} $$

$$ r = \frac{\sqrt{5}\sqrt{2}}{2} $$

$$ r = \frac{\sqrt{10}}{2} $$

So our final answers are:

Center:

$$ \boxed{\left(-\frac{1}{2}, \frac{3}{2}\right)} $$

And our radius is:

$$ \boxed{r = \frac{\sqrt{10}}{2}} $$

Note: Mcgraw's answer in the back of the book is actually incorrect.

---

## The Parabola

**For questions 407 and 408,** find the focus and directrix for the given
parabola.

---

**407.** $y^2 = 40x$

**Answer:**
