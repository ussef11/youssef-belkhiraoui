# Strong Random Password Generator PYTHON


import  random
letters = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z", "1" "2", "3", "4", "5", "6", "7", "8", "9", "0", "(", ")"]
x=0
while x < 10:
  a = random.randint(0,36)
  b = random.randint(0,36)
  c = random.randint(0,36)
  d = random.randint(0,36)
  e = random.randint(0,36)
  f = random.randint(0,36)
  g = random.randint(0,36)
  print(letters[a]+letters[b]+letters[c]+letters[d]+letters[e]+letters[f]+letters[g])
  x+=1

