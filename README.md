# pimpmycode
Please help me with this code. Please and Thanks...
def fibonacci(n):
    terms = [0,1]
    i=2
    while i<n:
        terms.append(terms[i-1]+terms[i-2])
        i=i+1
    return terms[n]
user_input = int(input("Enter n where n is the nth digit in the fibinacci sequence:"))
fibonacci(user_input)
