# What I learned

In the first lecture, I learned about the importance of using `===` (or `!==`) instead of `==` for accurate comparison checks. 

### Expressions tested in the REPL:
* Testing `"67" == 67` uses loose equality, which fails to check the type of the two values
* Testing `"67" === 67` uses strict equality, which skips coercion and evaluates to `false` because a string type does not match a number type.
* Testing `0 == ""` evaluates to `true` because loose equality coerces both values to their falsy equivalents before comparing them.

### REPL Snippet Tried:
```javascript
"67" == 67
"67" === 67
0 == ""
```

### REPL Output:
```
true
false
true
```
