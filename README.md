# Pr8_Numeros_pares_e_impares_3W_Luis_Daniel
Practica 8 Luis Daniel Molina Leyva 3W

# Ingresar un conjunto de numeros para informar si la cantidad ingresada es par o impar.
# Finalizar la lectura de datos ingresando -1

print('Ingrese un conjunto de numeros.')
print('Ingrese -1 para finalizar la lectura de datos. A continuacion se indicara si la cantidad ingresada es par o impar.')

inicio = 0
suma = 0

while inicio != -1:
    numero = int(input('Ingrese un numero: ')) #indica que se debe ingresar un numero
    suma += numero #Indica que los dos numeros escritos se sumaran
    if (suma % 2) == 0:
        if numero == -1: #Indica que cuando escrivs -1 se te indicara si el numero anterior es par o impar
            print('La cantidad ingresada es impar.') #Indica que la cantidad es impar
    else:
        if numero == -1: #Indica que cuando escrivs -1 se te indicara si el numero anterior es par o impar
            print('La cantidad ingresada es par.') #Indica que la cantidad es par

![image](https://github.com/user-attachments/assets/15b16836-fcce-4816-83aa-ed727444a830)

![image](https://github.com/user-attachments/assets/78bd51c5-9238-4cf0-bff9-b7c0ac89f30d)

