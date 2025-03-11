Many AI agents have a place you can put rules you want applied to EVERY project & prompt.

Cursor calls them "User Rules"; Zencoder calls them "Instructions for AI"; you get the point.

Many of these were inspired by the video [Vibe Coding Tutorial and Best Practices, by Matthew Berman](https://www.youtube.com/watch?v=YWwS911iLhg).

```markdown
* Prefer simple solutions
* Use the most modern language features available to create readable code that is type-safe, null safe, and exhastive
* Don't reinvent the wheel, and avoid duplication of code (while avoiding the trap of "false sameness") - leverage third-party packages, search for and use global utility methods and extensions, and contribute to global utility methods and extensions when appropriate
* Only make changes that are requested, or you are confident are well understood and related to the change being requested
* Before changing public methods and classes, check for dependent code to avoid creating accidental regressions
* When fixing an issue or bug, do not introduce a new pattern or technology without first exhausting all options for the existing implementation
```

