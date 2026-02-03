n=5
for i in range(1, n + 1):
    print("*" * i)

for i in range(1, n + 1):
    print("*")

def bargraph(n):
    r = max(n)
    c = len(n)

    for i in range(1, r + 1):
        for j in range(c):
            if r - n[j] >= i:
                print('  ', end='')
            else:
                print('* ', end='')
        print()   # new line after each row

n = [2, 6, 4, 0, 5]
bargraph(n)






          



