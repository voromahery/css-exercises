# CSS exercise 40: Shadows

There are two types of shadows:

1. Box Shadows, or the shadows that run around or inside a box
1. Text Shadwos, or the ghostly shadow outlines of text.

Let's do some research on these shadows…

1. `box-shadow` and `text-shadow` have very similar value syntax. Where do they differ?

- `box-shadow` works with all shadow properties.
- `text-shadow` doesn't work with inset.

2. If I wanted to create a hard-edge shadow, one that looks like a solid border, what combination of values would I need to use?

- You have to put `x`, `y`, `blur`, `thickness` and `colour`.

3. Is it possible to create a shadow on a circular element? What about a polygon?

- We can create a shadow on a circular element and inset but, with polygon it is impossible.

4. Is it possible to create multiple shadows on the same element?

- It is posssible to create multiple shadows on the same element by using **comma** to separate each shadow value.
