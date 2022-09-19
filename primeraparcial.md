
---
![ alt ](https://imgs.search.brave.com/71ZpZYIDKJFF4hyzvZ_Ka3co-bXu5mS0uoIjcv5uvy4/rs:fit:1200:687:1/g:ce/aHR0cDovL3d3dy51/Y29sLm14L2NvbnRl/bnQvY21zLzkvaW1VlVl/Z29sLm14L2NvbnRl/bnQvY21zUMG4VWQnQUWRMG4VWQuc)
# *UNIVERSIDAD DE COLIMA*   
## *FACULTAD DE INGENERIA MECANICA Y ELECTRICA* 
#### *CARRERA: INGENIERIA EN COMPUTACION INTELIGENT*
#### *ALUMNA: ANDREA KETZABEL MARIGAL RODRIGUEZ
#### *PROFRESOR: WALTER MATA  LOPÉZ 
---

_HOLA SOY ANDREA ESTUDIANTE DE ICI Y EN ESTE  TRABAJO PRESENTARE TODOS LOS EJERCICIOS QUE HICE EN
PRIMERA PARCIAL_

---
###  Imprimir

			print("Hola ici")
---
###  "markdown"

		#UNIVERSIDAD DE COLIMA
		## FACULTAD DE INGENERIA MECANICA Y ELECTRICA
		### INGENIERIA EN COMPUTACION INTELIGENTE
---
###  Interpolación de Cadenas

		nombre="ketzabel"
		edad=18
		print("hola",nombre,"tienes",edad,"años")
---
###  cuerdas

		mensaje=f"hola {nombre} ,tienes {edad} años"
		mensaje
		imprimir (mensaje)

		print(f"hola {nombre},tienes {edad} años")
---

---
###  Ejercicio 

- Escriba una función que mediante fstrings devuelva el mensaje "Hola -nombre- tienes -edad- años".
  Los argumentos de la función: año actual, año de nacimiento y nombre

	  nombre="kurt"
		edad=18

		def acto(nombre,edad):
    	 volver(nombre,edad)

	  mensaje=f"hola {nombre} tienes {edad}"
		imprimir (mensaje)
---
###  Fstrings aplicado
- EJEMPLO 

			num_materia=["No. ",1,2,3,4]
			name_materia=["Materia","Estructura de datos","Ecuaciones diferenciales","Programacion funcional","Metodos numericos"]
			name_profesor=["Profesor","Soto","Eli","Walter","Edgar"]              
			imprimir (f"{num_materia[0]:^5}{name_materia[0]:^30}{name_profesor[0]:<6}")
			para i en rango (1,5):
    			print(f"{num_materia[i]:^5}{name_materia[i]:<30}{name_profesor[i]:<6}")

- EJEMPLO 

			alumnes=["alexis","fernando",valeria",jason,"melissa"]
			nombre_materia=[6,8,6,8,7]
			nombre_materia2=[8,9,10,8,9]
			nombre_materia3=[8,8,7,6,9]
			nombre_materia4=[9,9,9,9,10]

			encabezado=["Nombre","Programacion funcional","Metodos numericos","Estructura de datos","Ingles"]

			def informe (fmt):
					print(f"{encabezado[0]:^{fmt}}{encabezado[1]:^{fmt}}{encabezado[2]:^{fmt}}{encabezado[3]:^{fmt}}{encabezado [4]:^{fmt}}")
					para i en el rango (5):
								print(f"{alumnos[i]: *^{fmt}}{nombre_materia[i]:* ^{fmt}}{nombre_materia2[i]: *^{fmt}}{nombre_materia3[i]:* ^{fmt }}{nombre_materia4[i]:*^{fmt}}")
			informar(20)
---
###  uso de funciones ,manejo de fstring


			# %%
			def saludo_edad_(nombre:str,a_nacimiento:int):
					edad= 2022-a_nacimiento
					print("Hola",nombre,"tienes",edad,"años")

			def calcular_edad(a_actual:int,a_nacimiento:int)->int:
					volver a_actual-a_nacimiento

			def saludo(nombre:str,edad:int):
					print ("Hola",nombre,"tienes",edad,"años")

			def cuadrados(numu:int,numd:int):
					retorno (numu *numu) + (numd* numero)
			si __nombre__ ==" __principal__ ":
					imprimir(cuadrados(2,2))
			# %%
			def tabla(x):
					para i en rango (11):
							imprimir(x,"*",i,"=",x*i)


			si __nombre__ ==" __principal__ ":
					imprimir(tabla(3))
			# %%
			#Clase del 12 de septiembre
			def tabla(t,n):
					para i en rango (1,n+1):
							imprimir(t,"*",i,"=",t*i)
			si __nombre__ ==" __principal__ ":
					imprimir(tabla(3,2))
			# %%
			def tabla(t:int,n:int,spc:int):
					para i en rango (1,t+1):
							para j en el rango (1,n+1):
									imprimir(f""i,"*",j,"=",i*j)
			t=int(input("¿Hasta que tablas quieres calcular?"))
			n=int(input("¿Hasta que número quieres calcular?"))
			tabla(t,n)
			# %%
			def tabla(t:int,n:int,spc:int):
					para i en rango (1,t+1):
							para j en el rango (1,n+1):
									imprimir(f"{i:^{spc}} * {j:^{spc}} = {i*j:^{spc}}")
			t=int(input("¿Hasta que tablas quieres calcular?"))
			n=int(input("¿Hasta que número quieres calcular?"))
			spc=int(input("¿Que espacio quieres?"))
			tabla(t,n,spc)
---
###  Ejercicio de clase
- escrbir una funcion que reciba como argumentos t y m, donde t es   
el limite de tablas que se deaearon tener y m hasta que valor 
de las tablas se desea. todas empeizan desde 1 , tablas de 
multiplicar

			def tablas(t:int,n:int):
					para i en el rango (1, t + 1):
							tabla(i,n,10)

			def tabla(t:int,n:int,spc:int):
					para i en rango (1,n+1):
							imprimir(f"{t:^{spc}}x{i:^{spc}}={t*i:^{spc}}")

			t=int(input("¿Hasta que tablas quieres calcular?"))
			n= int(input("¿Hasta que número quieres calcular?"))
			tabla(t,n)
###  Programas con operaciones
- Suma

			def suma(num:int,num2:int)->int: return numero+num2

			si __nombre__ == " __principal__ ":
					imprimir(suma(3,7))
- Multiplicación

			def multi(num: int, num2: int) -> int: return num * num2

			si __nombre__ == " __principal__ ":
			     imprimir (múltiples (3, 7))
- División

			def divisi(num: int, num2: int) -> float: return num / num2

			si __nombre__ == " __principal__ ":
					imprimir(divisi(3, 7))
- Cuadrado

			def cuadrado(num: int) -> int: return numero*num

			si __nombre__ == " __principal__ ":
					imprimir(cuadrado(3))
- Resto

			def resta(num: int, num2: int) -> int: return num - num2

			si __nombre__ == " __principal__ ":
					imprimir(resta(3, 7))
---
###  Programa listas

			i_lista=[1,2,3,4]
			imprimir (mi_lista)
			lista_vacia=[]
			imprimir(lista_vacia)


			mi_lista2=[1,"Hola",Verdadero,3.14,[1,2,3],(1,2,3),{1,2,3}]
			imprimir (mi_lista2)

			imprimir(len(mi_lista))
			imprimir (len (mi_lista2))
			print(f"Mi lista:{mi_lista}")

			print(f"No de elementos:{len (mi_lista)}")
			print(f"Primer elemento:{mi_lista[0]},{mi_lista[1]},{mi_lista[2]},{mi_lista[3]}")
			print(f"Primer elemento:{mi_lista[-1]},{mi_lista[-2]},{mi_lista[-3]},{mi_lista[-4]}")
- Rebanadas: Partes de una lista (rebanadas)

			imprimir(mi_lista[1:-1])
			imprimir(mi_lista[0:3])
			imprimir(mi_lista[0:])
			imprimir(mi_lista[:])
- Modificar listas

			mi_lista[2]="tres"
			imprimir (mi_lista)

			ml.extender([6,7,8])
			imprimir (ml)

			ml.insert(4,"cinco")
			imprimir (ml)

			del ml[5]
			imprimir (ml)

			ml.eliminar(2)
			imprimir (ml)

			ml.reverse()
			imprimir (ml)

			l1=[1,2,3]
			l2=l1[:]
			imprimir (l1)
			l1.reverse()
			imprimir (l1)
			imprimir (l2)
- Insertar elementos en una lista

			nueva_lista=[5,"seis",7,8]
			mi_lista[len(mi_lista):]=nueva_lista
			imprimir (mi_lista)

			mi_lista=[1,2,3,4]
			mi_lista.append("cinco")
			imprimir (mi_lista)

			ml=[]
			para i en el rango (1,5):
					ml.append(i)
			imprimir (ml)
- Programa que ordena elementos en una lista

			ld=[[5,4,6],[7,8,2,1],[3,4,5],[6,7]]
			print(f"Desordenado: {ld}")
			ld.sort()
			print(f"Ordenado: {ld}")

			ld=[5,4,6,7,8,2,1,3,4,5,6,7]
			S1= ordenado(ld)
			imprimir (S1)
			ld=[5,4,6,7,8,2,1,3,4,5,6,7]
			S2= ordenado(ld,reverse=True)
			imprimir (S2)

			ceros=[0,0,0,0,0,0,0,0,0]
			imprimir (ceros)
			ceros=[0]*9
			imprimir (ceros)

			valor_max=max(ld)
			imprimir (valor_max)

			valor_min=min(ld)
			imprimir(valor_min)

			cuatros=ld.cuenta(4)
			imprimir(cuatros)

			repetición=[]
			para i en rango (1,9):
					repe.append(ld.count(i))
			imprimir (repetir)			
---
###  Funciones

 		def saludo():

		print("Hola mundo")

		mi_funcion=saludo() #asignando la funcion
		saludo() #Invocando la funcion
		imprimir(mi_funcion)

		def saludo2():
        volver"Hola mundo"
		saludo2() #Invocacion

		mi_funcion2= saludo2()
		imprimir(mi_funcion2)

		un=5
		b=10
		res = f" La suma de {a}+{b} = {a+b}"
		imprimir (res)

		def suma(a,b):

         volver a+b

		res = f"La suma de {a}+{b} = {suma(a,b)}"
		imprimir (res)
