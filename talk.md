class: center, middle, inverse

# Simple example presentation

David Lindstedt, SMHI

---

<!-- use layout: true to set to all slides, no need for a headline like here -->
## Header and Footer

use layout; true to set header and footer to all slides.


.header-content[Template presentation header example]

<div id="footer-content">
    <p>
        <img src="img/SMHIlogo.png" style="width: 50px;"/>
        David Lindstedt
    </p>
</div>

---

# "Modes"

## Subheading

### subsubheading

Try **F**, **C** and **P** keys.

- F: Full screen
- C: Clone presentation, dual monitors
- P: Presentaion mode; try **C** and then **P**

---

## Slide with two columns

.left-column[
## Left heading

- Some
- Bullet
- Points
]

.right-column[
## Right heading

- Other
- Interesting
- Bullet points
]

---

## Code blocks are no problem

Here we have some Python code:

```python
from itertools import cycle

fizz = cycle(['', '', 'Fizz'])
buzz = cycle(['', '', '', '', 'Buzz'])

for i in range(1, 101):
    print((next(fizz) + next(buzz)) or i)
```

[Source](https://github.com/olemb/nonsense/blob/master/fizzbuzz/itertools_cycle.py)

---

## Images

An image fetched from the web:

![Sample image](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/The_Young_Cicero_Reading.jpg/316px-The_Young_Cicero_Reading.jpg)

---

## Local image
<img src="img/surftemp_ARCTIC24.png" style="width: 60%;"/>

.cite[Lindstedt et. al., Tellus (2015)]

---

background-image: url(img/neverforget.jpg)
class: background

# Background image

---

## Videos
<video width="400" controls>
  <source src="img/mov_bbb.mp4" type="video/mp4">
</video>

---

## Math equations
`\(E = mc^2\)`
`$$ \Gamma(t) = \pi \, \Im\left\{ \mathbf{x}_+^H(t) \, \frac{\mathrm{d}}{\mathrm{d} t}\mathbf{x}_+(t) \right\} $$`

---

## Unravel text

- figure 1

--
- figure 2

--
- figure 3

---

## Slide notes

- Press P, to get presentation mode and see if you have any notes..

???
This is my notes and only visible to me..
