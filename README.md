# ex1
def pobierz_dane(liczba_cyfr):
    lista=[]
    for i in range(liczba_cyfr):
        lista.append(int(input("podaj liczbe")))
    return lista

def parzysta(liczba):
    if liczba %2 == 0:
        return True
    else:
        return False


print("ile chcesz liczb")
cyfry=int(input())
lista=pobierz_dane(cyfry)

for i in lista:
    print(parzysta(i))
print(lista)
