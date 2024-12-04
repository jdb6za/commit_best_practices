# Day 3 - Be Explicit about Your Changes
Be explicit about your changes when committing. Your commit messages are a shorthand history of your code. They are useful only if they say what actually happened. Vague or generic messages may as well say "I touched the code" because the only information they convey is your name and the date. Do your future self a favor by making your commit messages explicit and _concise_.

## Why be Explicit?
Given its negative associations in English, some may be surprised by my choice to use "explicit" rather than another word, such as, "precise". Besides its usefulness as a hook, explicit conveys a desire for clear communication that avoids confusion caused by trivial details. The Oxford dictionary (according to Bing at least) defines "explicit" as:

**Explicit**: _adjective_ - "stated clearly and in detail, leaving no room for confusion or doubt"

Ultimately, the goal of a commit message is clear communication with your future self and colleagues. Commit messages should provide a level of detail that accurately describes your changes without creating confusion.

## Examples
Avoid vague commit messages.
```
Add function
```
Be explicit by saying what you added and why.
```
Add createObject function to populate Object containers
```

Avoid catchall commit messages.
```
Add Awesome Feature files
```
Be explicit by providing context for large commits.
```
Begin development of Awesome Feature by adding hpp and cpp files
```

## Tips for Writing Explicit Commit Messages
- Commit code as logical units. It is easier to be explicit about your changes if you group logical changes together into separate commits.
- Make smaller commits
- Focus on your purpose and stage of development. It might not be feasible to precisely describe all of your changes in a concise commit message, for example, initial development, early prototyping, or major refactoring. Instead, focus on why you made your changes and where you are at in the development.