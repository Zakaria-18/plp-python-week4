# PLP Python Week 4 - Make It Shorter & Your First Toolbox

## Files
- `welcome.py` - A single `welcome()` function that returns a greeting, called three times instead of repeating the same print line.
- `toolbox.py` - Three small functions: `double(number)`, `is_pass(score)`, and `greet(name, greeting="Hello")`, with test prints at the bottom.

## Reflection
The hardest function to write was `greet`, because of the optional
`greeting` parameter. I had to remember that a default value like
`"Hello"` means the function works both when I pass one argument and when I
pass two, and that I still need to build the returned string with the comma
and exclamation mark in the right places. The other two were easier because
`double` is just one multiplication and `is_pass` can simply return
`score >= 50` without an `if`.
