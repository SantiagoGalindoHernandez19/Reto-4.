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

.
-

SEGUNDA PARTE( HALLAR RAIZ CUADRADA 

a: real positivo o igual a 0

b: entero

inicio

Z=a

x=1

c= 0.1

si: z-x>c

entonces: 

z=(a+x)/2

sera un resultado aproximado 

x=a/z
fin



![RETO 4](https://user-images.githubusercontent.com/124641609/224517688-a5244a28-322b-4b4f-9983-38c3bb75883c.jpg)
