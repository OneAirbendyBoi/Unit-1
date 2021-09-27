#Ask the user for  2 numbers, A and B, Output TRUE if one of them is 10 or if their sum is 10.
a = int(input("Insert first number here: "))
b = int(input("Insert second number here: "))
c = a + b
if a == 10:
  print("TRUE")
else:
  if b == 10:
    print("TRUE")
  else:
    if c == 10:
      print("TRUE")
    else: print("FALSE")
