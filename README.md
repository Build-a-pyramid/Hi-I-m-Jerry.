# Hi-I-m-Jerry.
A million dreams
def Prime_number(i):
    n = i - 1
    flag = 0
    for j in range(2,n+1):
        if i % j == 0:
            flag = 0
            break
        else:
            flag = 1
    if ((i == 2) | (flag == 1)):
        print(i,end = ' ')
    else:
        return None
for i in range(2,100001):
    Prime_number(i)
