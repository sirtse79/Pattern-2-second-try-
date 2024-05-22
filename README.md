# Pattern-2-second-try-
It works ;)

size = int(input())

for i in range(size):
    if 0 < i < size - 1:
        stars = "*" + (size - 2) * " " + "*"
    else:
        stars = "*" * size

  print(stars)
