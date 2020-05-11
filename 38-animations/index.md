# CSS exercise 38: Keyframe animations

You've asked for looping and infinite animations… that's what Keyframe Animations are for!

No need for a higher-specificity selector to drive them too, you can set animations on the base styles of any element.

Let's do some research:

1. Keyframe Animation setup needs some unique code, what does it start with?

--> Keyframe Animation starts with `@keyframes`, selectors 0% to 100%.

1. What makes the keyframes code different to the rest of CSS?

--> Only keyframes code needs `{}` for nesting.

1. How do we use a keyframe animation we set up earlier as a property in a ruleset for an element?

--> We use `animation-name` and `animation-duration`(default: 0).

1. Keyframe animations have other keywords that aren't available in `transitions`, what are these keywords?

--> These keywords are `infinite`, `reverse`, `alternate`, `playstate`, `paused`, `running` and `alternate-reverse`.

1. How many properties can we animate at once?

--> We can animate as many properties as we want.

1. What properties are animatable?
--> Those properties are animatable:
- background
- background-color
- background-position
- background-size
- border
- border-bottom
- border-bottom-color
- border-bottom-left-radius
- border-bottom-right-radius
- border-bottom-width
- border-color
- border-left
- border-left-color
- border-left-width
- border-right
- border-right-color
- border-right-width
- border-spacing
- border-top
- border-top-color
- border-top-left-radius
- border-top-right-radius
- border-top-width
- bottom
- box-shadow
- clip
- color
- column-count
- column-gap
- column-rule
- column-rule-color
- column-rule-width
- column-width
- columns
- filter
- flex
- flex-basis
- flex-grow
- flex-shrink
- font
- font-size
- font-size-adjust
- font-stretch
- font-weight
- grid
- grid-area
- grid-auto-columns
- grid-auto-flow
- grid-auto-rows
- grid-column
- grid-column-end
- grid-column-gap
- grid-column-start
- grid-gap
- grid-row
- grid-row-end
- grid-row-gap
- grid-row-start
- grid-template
- grid-template-areas
- grid-template-columns
- grid-template-rows
- height
- left
- letter-spacing
- line-height
- margin
- margin-bottom
- margin-left
- margin-right
- margin-top
- max-height
- max-width
- min-height
- min-width
- object-position
- opacity
- order
- outline
- outline-color
- outline-offset
- outline-width
- padding
- padding-bottom
- padding-left
- padding-right
- padding-top
- perspective
- perspective-origin
- right
- text-decoration-color
- text-indent
- text-shadow
- top
- transform
- transform-origin
- vertical-align
- visibility
- width
- word-spacing
- z-index

