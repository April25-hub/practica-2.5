# practica-2.5
arzaba diaz april 3w
print(" ")

print("Arzaba Diaz April")

def numeros_loteria():

    """
    
    Pide los numeros triunfadores de la loteria y los muestra en orden de menor a mayor.
    
    """
    
    numeros_loteria = []

    
    
    while True:
    
        numero = input("Ingresa un numero triunfador de la loteria (o 'fin' para terminar): ")
        
        if numero.lower() == 'fin':
        
            break
        else:
            
            numeros_loteria.append(int(numero))



    numeros_loteria.sort()
    
    
    print("Numeros triunfadores de la loteria en orden de menor a mayor:")
    
    
    print(numeros_loteria)



# Llamar a la funcion

numeros_loteria()
![image](https://github.com/user-attachments/assets/8ee78d1b-77af-4eb2-a478-cdba1560a2c8)
![image](https://github.com/user-attachments/assets/28708c38-55a1-4ce9-a21f-aac43b733377)


