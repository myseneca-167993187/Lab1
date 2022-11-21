## The code below is for a python function that takes the birth date of a user via user input and returns their current age.

```
#!/usr/bin/env python3

from datetime import date

def age(birthday):
from datetime import datetime, date

print("Your date of birth (dd mm yyyy)")
date_of_birth = datetime.strptime(input("--->"), "%d %m %Y")

try:
    def calculate_age(born):
        today = date.today()
        return today.year - born.year - ((today.month, today.day) < (born.month, born.day))

    age = calculate_age(date_of_birth)

    print(age)

except TypeError:
    print('Please enter an int')



World():
	print(‘Hello World’)


	helloWorld()

