<h1>Universidad de Colima</h1>
<h2>Facultad de ingenieria mecanica y electrica</h2>
<h2>Ingenieria en computacion inteligente</h2>
<h2>Alumno: Sergio Valentin Ochoa Hernandez</h2>
<h2>Maestro: Dr. Walter Alexander Mata</h2>

<h3>1-Print</h3>
  
  print("Hola ICI")

<h3>2-Uso de encabezados MARKDOWN</h3>
  
    #Universidad de Colima
    ##Facultad de ingenieria mecanica y electrica
    ###Ingenieria en computacion inteligente

<h3>3-Interpolacion de cadenas</h3>
  
    name="Sergio"
    edad=19
    print("hola",name,"tienes",edad,"años")

<h3>4-fstrings</h3>
  
    mensaje=f"hola {name},tienes {edad} años"
    mensaje
    print(mensaje)
    print(f"hola {name},tienes {edad} años")

<h3>5-Definir funciones</h3>
  
    def saludo0():

      print("Hola mundo")

      mi_funcion=saludo()   
      saludo0()               
      print(mi_funcion)

    def saludo1():
      return"Hola mundo"
      saludo2() #Invocacion 

      mi_funcion2= saludo2()
      print(mi_funcion2)

      a=5
      b=10
      res=f" La suma de {a}+{b}={a+b}"
      print(res)

    def suma(a,b):

      return a+b

      res=f"La suma de {a}+{b}={suma(a,b)}"
      print(res)

<h3>6-Listas, sets, tuplas y diccionarios</h3>

	list_numeros = ["uno","dos","tres"]
	msg_numeros= f"Numeros:{list_numeros}"
	print(msg_numeros)
	
	tupla_numeros=("uno","dos","tres")
	msg_numeros=f"numeros:{tupla_numeros}"
	print(msg_numeros)
	
	set_numeros={"1","2","3","4","5","6","7","8","9","10"}
	print(set_numeros)
	
	dict_numeros={"1":"uno","2":"dos","3":"tres"}
	msg_dict_numeros=f"numeros:{dict_numeros}"
	print(msg_dict_numeros)
	
	dos=f"Numeros:{dict_numeros['2']}"
	print(dos)

<h3>7-Ejercicio de clase</h3>

<h4>Escribe una funcion usando fstrings y que retorne el mensaje "Hola (nombre) tienes (edad) años".Usando de argumentos: Año actual, año nacimiento y nombre</h4>

    nombre="Sergio"
    edad=19

    def act(nombre,edad):
      return(nombre,edad)

    mensaje=f"hola {nombre} tienes {edad}"
    print(mensaje)
  
<h3>8-fstrings aplicadas</h3>

  	num_materia=["No. ",1,2,3,4]
  	name_materia=["Materia","Estruct. de datos","Ecuaciones diferenciales","Prog. funcional","Metodos numericos"]
  	name_profesor=["Profesor","Soto","Elizabeth","Walter","Edgar"]              
  	print(f"{num_materia[0]:^5}{name_materia[0]:^30}{name_profesor[0]:<6}")
  	for i in range (1,5):
  		print(f"{num_materia[i]:^5}{name_materia[i]:<30}{name_profesor[i]:<6}")
      
<h3>8.2</h3>
  	
    alumno=["Jose","Miguel","Orlando","Jan","Dani"]
  	name_materia=[6,8,6,8,7]
  	name_materia2=[8,9,10,8,9]
  	name_materia3=[8,8,7,6,9]
  	name_materia4=[9,9,9,9,10]

  	encabezado=["Nombre","Prog. funcional","Ingles","Metodos numericos","Estruct. de datos"]

  	def reporte(fmt):
  			print(f"{encabezado[0]:^{fmt}}{encabezado[1]:^{fmt}}{encabezado[2]:^{fmt}}{encabezado[3]:^{fmt}}{encabezado[4]:^{fmt}}")
  			for i in range (5):
  						print(f"{alumno[i]:*^{fmt}}{name_materia[i]:*^{fmt}}{name_materia2[i]:*^{fmt}}{name_materia3[i]:*^{fmt}}{name_materia4[i]:*^{fmt}}")
  	reporte(20)

<h3>9-Programas hechos en clase con funciones y fstrings</h3>
		
		def saludo_edad_(nombre:str,a_nacimiento:int):
				edad= 2022-a_nacimiento
				print("Hola",nombre,"tienes",edad,"años")

		def calcular_edad(a_actual:int,a_nacimiento:int)->int:
				return a_actual-a_nacimiento

		def saludo(nombre:str,edad:int):
				print ("Hola",nombre,"tienes",edad,"años")

		def cuadrados(numu:int,numd:int):
				return (numu*numu) + (numd*numd)
		if __name__=="__main__":
				print(cuadrados(2,2))
		# %%
		def tabla(x):
				for i in range (11):
						print(x,"*",i,"=",x*i)


		if __name__=="__main__":
				print(tabla(3))
	
		

<h3>Programas con operaciones</h3>
<h4>Funcion suma</h4>
  	
    def suma(num:int,num2:int)->int: return num+num2

  	if __name__ == "__main__":
  			print(suma(5,9))
        
<h4>Funcion Resta</h4>

  	def resta(num: int, num2: int) -> int: return num - num2

  	if __name__ == "__main__":
  			print(resta(3, 7))

<h4>Funcion Multiplicacion</h4>
  	
    def multi(num: int, num2: int) -> int: return num * num2

  	if __name__ == "__main__":
  	     print(multi(5, 9))

<h4>Funcion Division</h4>

  	def div(num: int, num2: int) -> float: return num / num2

  	if __name__ == "__main__":
  			print(div(5, 9))


<h4>Funcion Cuadrado</h4>

  	def cuadrado(num: int) -> int: return num*num

  	if __name__ == "__main__":
  			print(cuadrado(3))


<h3>Programa con listas</h3>

		i_lista=[1,2,3,4]
		print(mi_lista)
		lista_vacia=[]
		print(lista_vacia)


		mi_lista2=[1,"Hola",True,3.14,[1,2,3],(1,2,3),{1,2,3}]
		print(mi_lista2)

		print(len(mi_lista))
		print(len(mi_lista2))
		print(f"Mi lista:{mi_lista}")

		print(f"No de elementos:{len (mi_lista)}")
		print(f"Primer elemento:{mi_lista[0]},{mi_lista[1]},{mi_lista[2]},{mi_lista[3]}")
		print(f"Primer elemento:{mi_lista[-1]},{mi_lista[-2]},{mi_lista[-3]},{mi_lista[-4]}")

<h4>Partes de lista(slices)</h4>

  	print(mi_lista[1:-1])
  	print(mi_lista[0:3])
  	print(mi_lista[0:])
  	print(mi_lista[:])

<h4>Modificar listas</h4>

  	mi_lista[2]="tres"
  	print(mi_lista)
  	
  	ml.extend([6,7,8])
  	print(ml)

  	ml.insert(4,"cinco")
  	print(ml)

  	del ml[5]
  	print(ml)

  	ml.remove(2)
  	print(ml)

  	ml.reverse()
  	print(ml)

  	l1=[1,2,3]
  	l2=l1[:]
  	print(l1)
  	l1.reverse()
  	print(l1)
  	print(l2)

<h4>Insertar elementos en lista</h4>

  	new_lista=[5,"seis",7,8]
  	mi_lista[len(mi_lista):]=new_lista
  	print(mi_lista)

  	mi_lista=[1,2,3,4]
  	mi_lista.append("cinco")
  	print(mi_lista)

  	ml=[]
  	for i in range(1,5):
  			ml.append(i)
  	print(ml)

<h4>Ordenar en lista</h4>

  	ld=[[5,4,6],[7,8,2,1],[3,4,5],[6,7]]
  	print(f"Desordenado: {ld}")
  	ld.sort()
  	print(f"Ordenado: {ld}")

  	ld=[5,4,6,7,8,2,1,3,4,5,6,7]
  	S1= sort(ld)
  	print(S1)
  	ld=[5,4,6,7,8,2,1,3,4,5,6,7]
  	S2= sort(ld,reverse=True)
  	print(S2)

  	ceros=[0,0,0,0,0,0,0,0,0]
  	print(ceros)
  	ceros=[0]*9
  	print(ceros)

  	valor_max=max(ld)
  	print(valor_max)

  	valor_min=min(ld)
  	print(valor_min)

  	cuatros=ld.count(4)
  	print(cuatros)

  	repe=[]
  	for i in range (1,9):
  			repe.append(ld.count(i))
  	print(repe)			

<h3>Ejercicio clase</h3>

<h4>funcion que reciba como argumentos t y m, donde t es el limite de tablas de multiplicar que se desean obtener y m hasta que valor de las tablas de multiplicar se desea</h4>

    print("En este programa se pediran 2 valores para mostrar en pantalla las tablas de multiplicar")

    inicio_t=1
    t=int(input("Ingresa el limite de las tablas de multiplicar\n"))
    inicio_m=1
    m=int(input("Cantidad de valores de las tablas de multiplicar\n"))

    def multiplicaciones(t,m):
        for val1 in range(inicio_t, t + 1):
            print(f'Tabla de multiplicar del {val1}:')
            for val2 in range(inicio_m, m + 1):
                print(f'{ val1 } x { val2 } = { val1 * val2 }')
            print()

    multiplicaciones(t,m)
