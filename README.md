# Reto-4.
Reto No.4



def numeroPrimo(n):

    if n < 2:
    
        return False
    for i in range(2, n):
        if n % i == 0:
            return False
    return True


def cantidad(n):

    c = 0
    i = 0
    while c < n:
        i += 1
        if numeroPrimo(i):
            c += 1
            print(i)


cantidad(25)



