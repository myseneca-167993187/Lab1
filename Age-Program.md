## The code below is for a python function that takes the birth date of a user via user input and returns their current age.

```
#!/usr/bin/env python3

from datetime import date

def age(birthday):
    present = date.today()
    age = present.year - birthday.year - ((present.month, present.day) < (birthday.month, birthday.day))
    return age

print(age(date(2001, 10, 15)))

```
