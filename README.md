# Calculator
print ""
print "This is a calculator!"
print ""
print "What type of calculation would you like to do?"
print "1. Addition 2. Subtraction 3. Multiplication 4. Division"

while True:
	typecalc = input()
	if typecalc == 1 or typecalc == 2 or typecalc == 3 or typecalc == 4:
		break
	else:
		print "Please enter a number between 1 and 4."

print ""

number1 = input("What is the first number in the calculation?")
number2 = input("What is the second number in the calculation?")

print ""

if typecalc == 1:
	print "Result:"
	print number1 + number2
	
if typecalc == 2:
	print "Result:"
	print number1 - number2

if typecalc == 3:
	print "Result:"
	print number1 * number2
	
if typecalc == 4:
	print "Result:"
	print number1 / number2

print ""
print "Thanks for using the calculator!"
