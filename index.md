
miLista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Encontrar =5
Encontrado = False

def encontrarNumero(Encontrar):
    for i in range(len(miLista)):
        if miLista[i]==Encontrar:
            Encontrado=True
            print("Elemento encontrado en el índice= ",i)
        else:
            Encontrado=False
            print("Elemento ausente")

encontrarNumero(Encontrar)
