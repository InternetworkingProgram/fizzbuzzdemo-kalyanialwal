![Open in Codespaces](https://classroom.github.com/assets/open-in-codespaces-abfff4d4e15f9e1bd8274d9a39a0befe03a0632bb0f153d0ec72ff541cedbe34.svg)
## FizzBuzz

FizzBuzz is a game that has gained in popularity as a programming assignment to
weed out non-programmers during job interviews. The object of the assignment is
less about solving it correctly according to the below rules and more about
showing the programmer understands basic, necessary tools such as
`if`-/`else`-statements and loops. The rules of FizzBuzz are as follows:

For numbers 1 through 100,

* if the number is divisible by 3 print Fizz;
* if the number is divisible by 5 print Buzz;
* if the number is divisible by 3 and 5 (15) print FizzBuzz;
* else, print the number.
#for loop that traverses numbers from 1 to 100
for i in range(1,101):
  #check if number is divisible by both 3 and 5
  if(i%3==0 and i%5==0):
    print("FizzBuzz")
  #check if number is divisible by 3
  elif(i%3 == 0):
    print("Fizz")
  #check if number is divisible by 5
  elif(i%5 == 0):
    print("Buzz")
  #if not divisible by either of them print the i
  else:
    print(i)
