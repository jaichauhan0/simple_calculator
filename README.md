# simple_calculator
def add(x,y):
	return x+y
def sub(x,y):
	return x-y
def mult(x,y):
	return x*y
def div(x,y):
	return x/y

				
print("PLEASE SELECT 1/2/3/4")
print("1.ADDITION")
print("2.SUBTRACTION")
print("3.MULTIPLY")
print("4.DIVIDE")

choice = int(input("PLEASE SELECT OPERATOR 1/2/
3/4 :"))
print(f"YOU SELECTED OPTION {choice}")
num1 = float(input("PLEASE ENTER FIRST NUMBER: 
"))
print(f"YOU ENTERED {num1}")
num2 = float(input("PLEASE ENTER SECOND 
NUMBER: "))													
print(f"YOU ENTERED {num2}")
if choice == 1:
	print(f"ADDITION OF {num1} AND {num2} IS 
{add(num1,num2)}")
elif choice == 2:
	print(f"SUBTRACTION OF {num1} AND {num2} IS 
{sub(num1,num2)}")
elif choice == 3:
	print(f"MULTIPLICATION OF {num1} AND {num2} 
IS {mult(num1,num2)}")
elif choice == 4:
	print(f"DIVISION OF {num1} AND {num2} IS 
{div(num1,num2)}")
else:
	print("INVALID INPUT")
