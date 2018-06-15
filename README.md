# assignment-6
#q1
>>> a = [int(x) for x in input().split()]
1 2 3 4 5 6 7 8 9 10
>>> a
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
#q2
var = 1
  while var == 1: #infinte
	num = raw_input("enter number : ")
	print ("you entered :",num)
#q3
>>> b = [int(x) for x in input().split()]
1 2 3 4
>>> b
[1, 2, 3, 4]
>>> c = [i**2 for i in b]
>>> c
[1, 4, 9, 16]
#q5
>>> evenn=[]
>>> for n in range(1,101):
	if n % 2 == 0:
		evenn.append(n)

		
>>> evenn
[2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64, 66, 68, 70, 72, 74, 76, 78, 80, 82, 84, 86, 88, 90, 92, 94, 96, 98, 100]
#q6
def pat(n):
	for i in range(0,n):
		for j in range(0,i+1):
			print("*",end="")
			print("\r")

			
>>> n=4
>>> pat(n)

