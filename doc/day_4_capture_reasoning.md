# Day 4 - Capture Your Reasoning
Why you did something is very often more important that what you did. This is as true when writing Git commits as it is in life. Writing concise commit messages that explicitly describe only your intermediate changes is like writing a story lacking in character motivation. You might elegantly describe your protagonist going from place to place doing this or that, but the reader is left wondering why. Whether it is colleagues reviewing your code or your future self coming back to it after a couple of years, readers of your code want to know why you wrote what you wrote.

## Examples of Adding Reasoning to Commit Messages
The commit below concisely and explicitly describes a change made to `GreatClass`, but it does not say why the developer made that change.
```
Refactor the specialFunction in GreatClass
```

Adding a little to the commit description and utilizing the commit body makes this commit much more valuable.
```
Refactor GreatClass's specialFunction to make it faster

specialFunction had an extra for loop that made it take twice as lone as necessary.
```

Likewise, the commit message below may do a good job succinctly describing a large change, but it lacks motivation.
```
Change Ultra's pick order to prioritize center picks
```

A slight rewording makes it clear that this is an important change.
```
Improve Ultra's reliability by prioritizing center picks
```

## Tips for Capturing Your Reasoning in Commit Messages
- Ask yourself: "Why are these changes necessary?" Knowing why your changes are important is the first step in being able to explain it to others.
- Focus on the big picture. As developers, we are constantly looking at the details, stepping back can help you see how your individual commits fit into a larger design.
- Don't be afraid to use the body of a commit message. Capturing your reasoning in an 80 character commit description is hard, so use the commit body to fully explain yourself (see Day 1 for the parts of a commit message).