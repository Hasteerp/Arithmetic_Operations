# Arithmetic_Operations
Write a program that will perform the four basic arithmetic operations (addition, subtraction, multiplication, and division) on pairs of fractions, producing answers in standard fractional form. Specifically, your program should repeatedly perform the following actions.  Read a character representing an operation. This will be one of the characters +, -, *, /, or E. The E signals the end of the data; reading it should cause the program to terminate. Read four integers representing the numerator and denominator of a first fraction followed by the numerator and denominator of a second fraction. Perform the indicated operation and print the results in the appropriate form as illustrated in the examples that follow. Once the results are printed, the program should loop back and start over, note that to terminate and exit the program ‘E’ should be entered as illustrated. It is your responsibility to avoid divide by zero. All divide by zero cases should be detected and prevented. In such cases, the program should alert the user with the message: Give values: 1 0 3 4 output: 1/0 * 3/4 Invalid expression! OR Give values: 3 5 0 7 output: 3/5 / 0/7 Invalid expression It is also your responsibility to detect illegal operations. Only one of the four (+, -, *, /) operations or E to stop, id permitted at the start, else a message should warn the user and then the program should allow the user to try again. Give an operation (+, -, *, /) E to stop:9 output: Invalid operation! Try again. Give an operation (+,-,*,/) $ to stop: Notice that integer results should be written as such, as in (c), and negative results should have only a negative sign on their numerator, as in (d). It is not necessary to reduce fractions to lowest terms, as in (a). In the examples, the input is shown on one line.  (a)  Give an operation (+, -, *, /) E to stop: + &lt;enter> Give values: 1 3 -19 -8&lt;enter> output: 1/3 + -19/-8 = 65/24 (b)  Give an operation (+, -, *, /) E to stop: /&lt;enter> Give values: 2 -5 3 -7&lt;enter> output: 2/-5 / 3/-7 = 14/15 (c)  Give an operation (+, -, *, /) E to stop: -&lt;enter> Give values: 5 2 1 2&lt;enter> output: 5/2 - 1/2 = 2 (d)  Give an operation (+, -, *, /) E to stop:*&lt;enter> Give values: 21 4 7 -3&lt;enter> output: 21/4 * 7/-3 = -147/12 (e)  Give an operation (+,-,*,/) $ to stop:+ &lt;enter> Give values: 1 0 3 4&lt;enter> output: 1/0 + 3/4 Invalid expression! OR  Give an operation (+, -, *, /) E to stop:/&lt;enter> Give values: 3 5 0 7&lt;enter> output: 3/5 / 0/7 Invalid expression! (f)  Give an operation (+, -, *, /) E to stop: E&lt;enter>    Hints:  Consider designing your program flow before starting coding. Use flowchart of pseudocode. Consider validating the four operations using Boolean logic. Consider combining if…else and switch for decision making.
