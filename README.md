# pimpmycode
Please help me with this code. Please and Thanks...
Current projects: the code in MAIN seems to work in Python2 but not in Python3 but I cannot figure out what the specific issue is
Here is why I think it works in 2 (https://www.youtube.com/watch?v=-BE7FEouGeI&t=350s) and here is the error I get when I run it in 3
IndexError                                Traceback (most recent call last)
<ipython-input-132-acb2fc047227> in <module>
     84     return terms[n]
     85 user_input = int(input("Enter n where n is the nth digit in the fibinacci sequence:"))
---> 86 fibonacci(user_input)
     87 
     88 

<ipython-input-132-acb2fc047227> in fibonacci(n)
     82         terms.append(terms[i-1]+terms[i-2])
     83         i=i+1
---> 84     return terms[n]
     85 user_input = int(input("Enter n where n is the nth digit in the fibinacci sequence:"))
     86 fibonacci(user_input)

IndexError: list index out of range
