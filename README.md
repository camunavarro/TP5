1) Escribir un programa que almacene las materias de un curso (por ejemplo Matemáticas,
Física, Química, Historia y Lengua) en una lista y la muestre por pantalla.

materias =  ["Matemáticas", "Física", "Química", "Historia", "Lengua"]

print(materias)

---------------------------------------------------------------------------------------------------
2) Escribir un programa que almacene las materias de un curso (por ejemplo Matemáticas,
Física, Química, Historia y Lengua) en una lista y la muestre por pantalla el mensaje Yo estudio
<materia>, donde <materia> es cada una de las materias de la lista.
 
materias =  ["Matemáticas", "Física", "Química", "Historia", "Lengua"]

for materia in materias:
    print(f"Yo estudio {materia}")
  
---------------------------------------------------------------------------------------------------
3) Escribir un programa que almacene las materias de un curso (por ejemplo Matemáticas,
Física, Química, Historia y Lengua) en una lista, pregunte al usuario la nota que ha sacado en
cada materia, y después las muestre por pantalla con el mensaje En <materia> has sacado
<nota> donde <materia> es cada una de las asignaturas de la lista y <nota> cada una de las
correspondientes notas introducidas por el usuario.
  
materias =  ["Matemáticas", "Física", "Química", "Historia", "Lengua"]
notas = []

for materia in materias:
    nota = int(input(f"¿Que nota te sacaste en {materia}?: "))
    notas.append(nota)

for calificacion_materia in range(len(materias)):
    print(f"En {materias[calificacion_materia]} obtuviste un {notas[calificacion_materia]}")
  
---------------------------------------------------------------------------------------------------
4) Escribir un programa que pregunte al usuario los números ganadores de la lotería, los
almacene en una lista y los muestre por pantalla ordenados de menor a mayor.

---------------------------------------------------------------------------------------------------  
5) Escribir un programa que almacene en una lista los números del 1 al 10 y los muestre por
pantalla en orden inverso separados por comas.

numeros = [1,2,3,4,5,6,7,8,9,10]

for indice in range (1,11):
    print(numeros[-indice],end=",")

--------------------------------------------------------------------------------------------------- 
6) Escribir un programa que almacene las materias de un curso (por ejemplo Matemáticas,
Física, Química, Historia y Lengua) en una lista, pregunte al usuario la nota que ha sacado en
cada materia y elimine de la lista las materias aprobadas. Al final el programa debe mostrar
por pantalla las materias que el usuario tiene que recursar.
NOTA: se aprueba con 4.. 

materias =  ["Matemáticas", "Física", "Química", "Historia", "Lengua"]
materias_aprobadas = []
materias_desaprobadas = []

for materia in materias:
    nota = float(input(f"¿Que nota te sacaste en {materia}?: "))

if nota >= 4:
    materias_aprobadas.append(materia)
else:
    materias_desaprobadas.append(materia)

print(f"Tenes que recursar: {materias_desaprobadas}")
  
#¿Porque solo me trae la ultima?

 ---------------------------------------------------------------------------------------------------  
7) Escribir un programa que almacene el abecedario en una lista, elimine de la lista las letras
que ocupen posiciones múltiplos de 3, y muestre por pantalla la lista resultante.


  
 --------------------------------------------------------------------------------------------------- 
8) Escribir un programa que pida al usuario una palabra/frase e informe por pantalla si es un
palíndromo.
NOTA: un palíndromo es una palabra/frase que se lee igual de izquierda a derecha que de
derecha a izquierda, ej: “Amad a la dama”.
NOTA2: ignoren mayúsculas y minúsculas.

--------------------------------------------------------------------------------------------------- 
9) Escribir un programa que pida al usuario una palabra y muestre por pantalla el número de
veces que contiene cada vocal.

---------------------------------------------------------------------------------------------------  
10) Escribir un programa que almacene en una lista los siguientes precios, 50, 75, 46, 22, 80,
65, 8, 23, 15, 5, 86, 43, 11 y muestre por pantalla el menor y el mayor de los precios.

---------------------------------------------------------------------------------------------------  
11) Escribir un programa que almacene los vectores (1,2,3) y (-1,0,2) en dos tuplas y muestre
por pantalla su producto escalar.
NOTA: channn….
NOTA2: producto escalar de (a,b,c) . (d,e,f) = a.d + b.e + c.f
12) Escribir un programa que almacene las matrices A y B en dos tuplas y muestre por pantalla
su producto.
𝐴 = (
1 2 3
4 5 6
) 𝑦 𝐵 = (
1 2
3 4
5 6
)
NOTA: buscar producto matricial en google…
