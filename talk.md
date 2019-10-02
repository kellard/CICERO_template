class: center, middle

# Simple example presentation

## Author

---

## Another slide

Try **F** and **P** keys.

- A bullet point
- Another convincing argument

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
<!-- Need to fit if using markdown -->
<!-- [Surface](img/surface.jpg) -->

<!-- html way -->
<img src="img/surftemp_ARCTIC24.png" style="width: 60%;"/>

.cite[Lindstedt et. al., Tellus (2015)]

---

## Videos
<video width="400" controls>
  <source src="img/mov_bbb.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

---

## Math equations
`\(E = mc^2\)`
`$$ \Gamma(t) = \pi \, \Im\left\{ \mathbf{x}_+^H(t) \, \frac{\mathrm{d}}{\mathrm{d} t}\mathbf{x}_+(t) \right\} $$`

---

## Unravel text

- figure 1

---

count: false
## Unravel text

- figure 1
- figure 2

---

count: false
## Unravel text

- figure 1
- figure 2
- figure 3

---

## Unravel text (better way, not solved)
use countIncrementalSlides see

https://github.com/gnab/remark/wiki/Markdown#count

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
