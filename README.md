quest = input("Выбирете операцию: (+,-,*,**,/): ")

first = float( input("Введите первое число: ") )
second = float( input("Введите второе число: ") )

if quest == "+":
	ex = first + second
	print("Ответ: " + str(ex))

elif quest == "-":
	ex = first - second
	print("Ответ: " + str(ex))

elif quest == "*":
	ex = first * second
	print("Ответ: " + str(ex))

elif quest == "/":
	ex = first / second
	print("Ответ: " + str(ex))

elif quest == "**":
	ex = first ** second
	print("Ответ: " + str(ex))

else:
	print("Операция нарушена (Возожная причина - неверно введенные данные.)")
I would like to improve this calculator by adding more operations.
