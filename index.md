## Welcome to Test PAge Zero

#Constructed and edited by Isaac D Dawson

This site serves as a generic test site, consturected to help me practise creating, aditing, and uploading sites to GitHub Pages.

There isn't really anything here, so I'm going to post some example python code here, Enjoy

```python
import random as rand

language = ["and", "Or", "But", "not"]

def string_karkatenate(*args: str) -> str:
    outval = ""
    for i in args:
        if rand.randint(0, 1) == 1:
            outval += f"{rand.choice(language)} {i} "
        else:
            outval += f"{i.strip()} "
    return outval.upper().strip()

print(string_karkatenate("Test1", "Option2", "Third example"))
```

More will be added to this site in future, maybe.
