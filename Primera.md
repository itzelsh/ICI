#Primera Parcial: Avanzados de programación
## Problemas resueltos en clase con el lenguaje Python
###Ejercicio 1. Imprimir un mensaje y un nombre
#### 1.1 Descripción del problema
Escribir una función que reciba un mensaje y un nombre
y escribe en panatalla "__mensaje nombre__"
#### 1.2 Codigo  
'' python
def mensaje(msg:str,nom:str)->str:
 return f"{msg} {nom}"
 '''
 #### 1.3 Implementación 
 ''' python
 print(mensaje("Buen dia,"Carmen"))
 '''
 #### 1.4 Salida
 ''''
 Buen dia Carmen
 '''
 ### Ejercicio 2. Imprimir  
 #### 2.1 Descripcion del problema 
 Escribir 2 números por pantalla y mostramos 2 resultados, la suma y el cuadrado que vienen dados por 
 dos funciones del mismo nombre
 #### 2.2 Codigo 
 ''' python
def cuadrado(n: int)->int|float: return n*n
def suma(a:int|str,b:int|str)->int|str: return a+b
  '''
  ### 2.3 Implementación 
 ''' python
print(suma(1, 1))
print(suma("Hola", "mundo"))
print(suma(1, "hola"))
print(cuadrado(2))
 '''
 #### 1.4 Salida
 ''''
 Hola mundo
 hola
 '''
  
 ###Ejercicio 3. 
#### 1.1 Descripción del problema
Escribir una funcion que tenga ciertos parametros 
#### 1.2 Codigo
'' python
def sumar(a: int|float,b: int|float)->int|float:
    return a+b
def cuadrado(a: int|float,b: int|float)->int|float:
    return a*a
def restar(a: int|float,b: int|float)->int|float:
    return a-b
def multiplicar(a: int|float,b: int|float)->int|float:
    return a*b
def dividir(a: int|float,b: int|float)->int|float:
    return a/b
 '''
 #### 1.3 Implementación 
 ''' python
 '''
 #### 1.4 Salida
 ''''
 Buen dia Carmen
 '''
 ###Ejercicio 4. 
#### 1.1 Descripción del problema
Escribir una función que reciba un mensaje y un nombre
y escribe en panatalla "__mensaje nombre__"
#### 1.2 Codigo
'' python
def mensaje(msg:str,nom:str)->str:
 return f"{msg} {nom}"
 '''
 #### 1.3 Implementación 
 ''' python
 print(mensaje("Buen dia,"Carmen"))
 '''
 #### 1.4 Salida
 ''''
 Buen dia Carmen
 '''
 ###Ejercicio 5. 
#### 1.1 Descripción del problema
Escribir una función que reciba un mensaje y un nombre
y escribe en panatalla "__mensaje nombre__"
#### 1.2 Codigo
'' python
def mensaje(msg:str,nom:str)->str:
 return f"{msg} {nom}"
 '''
 #### 1.3 Implementación 
 ''' python
 print(mensaje("Buen dia,"Carmen"))
 '''
 #### 1.4 Salida
 ''''
 Buen dia Carmen
 '''
 
 
 
 
