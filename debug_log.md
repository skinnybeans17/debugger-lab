# Debug Log

**Explain how you used the VSCode debugger tools to uncover the bugs in Exercise 7. Be specific. What breakpoints did you set? Where did you step to? What made you realize the error?**

_Example: I set a breakpoint on line 5 and stepped until line 12. There, I discovered that the `x` variable had a value of `-3`, whereas it should have had a value of `7`. That made me realize that we should be adding the two numbers `x` and `y`, instead of subtracting._

When I started on this, whenever I tried to run the file, it was only printing out one word, which is "fantastic". I noticed the error was that the wrong variables were used. Specifically on lines 10 and 13. I simply swapped 'start_str' and 'sentence' for the tenth line, and replace 'start_str' with 'sentence' for the thirtenth line. After that, the bug was fixed! It runs as it should now!