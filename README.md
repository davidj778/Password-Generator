[Main Page](https://github.com/davidj778/davidj778)

# Password Generator

For this lab, I built a random password generator in python. 

## Step 1:
First, in order to generate random strings of text, you have to import the random module. 

The string module is imported for the sole purpose of accessing predefined sets of characters for a variable that will be added later.
```python
# Example Python script
import random
import string
```

## Step 2:
```python
# Example Python script
def generate_password(Length: int = 10):
```

## Step 3:
```python
# Example Python script
alphabet = string ascii_letters + string digits + string-punctuation
```

## Step 4:
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
```python
# Full Python script
import random
import string

def generate_password(Length: int = 10):
    alphabet = string ascii_letters + string digits + string-punctuation
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


