import random

elements =  "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
a = int(input('введите длину пароля:'))

password = ''

for i in range(a):
    password += random.choice(elements)

print(password)
