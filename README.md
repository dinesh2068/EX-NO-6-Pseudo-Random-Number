# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# Algorithm:

1. Initialize the random number generator with or without a seed.  
2. Generate pseudorandom numbers using the library's function.  
3. Use the generated numbers as required in the application.

# Program:
```
import random
from datetime import datetime

random.seed(datetime.now().timestamp())  
for i in range(5):
    print(random.randint(0, 10), end="\n")
```

# Output:

![image](https://github.com/user-attachments/assets/af23a9c2-4c72-4827-8b79-7d8874fb878d)

# Result:

Thus Pseudorandom Number Generation Using Standard library has been executed successfully.
