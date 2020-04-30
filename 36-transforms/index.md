# CSS exercise 36: Transforms

The `transform` property is a powerful way to change many aspects of an element, mainly through applying changes to the element's geometry.

Let's look a little deeper at `transform`.

1. Name the functions we can use in a `transform`'s value?
- scale ()
- matrix()
- rotate()
- translate()
- skew()
- perspective()

1. Why do we have to use separate functions, in order, and as values, e.g. `transform: scale(0.5) rotate(45deg);` when we could have had separate properties like: `transform-scale: 0.5;`, or `transform-rotate: 45deg`?

--> Only the last function works.

1. Often, we want to move the central pin or axis of the transform away from its default position. What property do we use to set that?

--> We use `transform: translate()`.

1. Why is it preferable to use `transform: translate()` rather than `position` and its associated properties?

--> If we use `transform: translate()`, we don't have to care about `margin` anymore, it also saves lots of time rather than writing a whole bunches of `position` properties.

1. When an element is translated / transformed, what happens to the flow of the document? Therefore, what layout method is `transform` similar to?

--> When an element is translated / transformed, it doesn't have any effect on the flow of the document.

--> `transform` is similar to `position`.

1. What problems can you run in to when overriding a `transform` in a more specific selector?

--> The default value is still applied.

1. If we want to go 3D, we need to use another property to set the view over the scene. What is that property?

--> We need `transform: translate3d()`, `perspective()` and `transform-style: presence3d`.

1. We can control what the transform uses in its calculations in terms of the box model. What property can we use to adjust this?

--> To adjust this, we can use `custom properties`.
