[Main Page](https://github.com/davidj778/davidj778)

# Password-Generator

For this lab, I built a random password generator in python. 

```python
# Example Python script
import random
import string
```

```python
# Example Python script
def generate_password(Length: int = 10):
```

```python
# Example Python script
alphabet = string ascii_letters + string digits + string-punctuation
```

```python
# Example Python script
password = ''.join(random.choice(alphabet) for i in range(length))

return password
```

```python
# Example Python script
password = generate_password()
print(f"Generated password: {password)")
```
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


