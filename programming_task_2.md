mut = 1
x = 1
while mut <= 10:
  n = input("insert number here: ")
  for l in n:
    mut *= int(l)
    x += 1
  print(x)
