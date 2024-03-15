[Main Page](https://github.com/davidj778/davidj778)

# Password Generator

For this lab, I built a random password generator in python. 

## Step 1:
First, in order to generate random strings of text, you have to import the "random" module. 

The "string" module is imported for the sole purpose of accessing predefined sets of characters for a variable that will be added later.
```python
# Example Python script
import random
import string
```

## Step 2:
Next, we want to create the body of text that will generate the passwords. To do this, we will add the "def" function to add a reusable block. 

I then defined the "generate_password" function that will generate random passwords with a specified length.
```python
# Example Python script
def generate_password(length: int = 10):
```

## Step 3:
For the next line of code, we want to add a variety of characters to generate our passwords. This is done by creating a string “alphabet”, which will concatenate ASCII letters(lower and uppercase), digits and punctuation characters.
```python
# Example Python script
alphabet = string.ascii_letters + string.digits + string.punctuation
```

## Step 4:
You add the ‘’ to ensure that there will not be any spaces between the characters generated. The “.join” concatenates the characters into a single string.

The “random.choice” function is pulled from the “random” module which randomly selects a character for the “alphabet” string.

The “for i in range(length)” repeats “random.choice(alphabet)” operation length a certain amount of times.

Finally, “return password” returns the new password to the original caller(generate_password).
```python
# Example Python script
password = ''.join(random.choice(alphabet) for i in range(length))

return password
```

## Step 5:
```python
# Example Python script
password = generate_password()
print(f"Generated password: {password)")
```

## Final Result:
The end result generates unique password everytime the script runs.
```python
# Full Python script
import random
import string

def generate_password(length: int = 10):
    alphabet = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(alphabet) for i in range(length))
    return password

password = generate_password()
print(f"Generated password: {password)")

# Output:
# Generated password: HinWNv9_]M
# Generated password: uR-pTFR04,
# Generated password: <otNKWD<m
# Generated password: 8&Pm.5-{DS
```


