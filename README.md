# Flow-3
En este repositorio se encuentra el ejercicio de Flow 3

## Ejercicio
En este ejercicio se utilizarán nuevos nodos dashboard, que sirven para crear gráficas de diferentes tipos, y que se modifiquen conforme se reciben diferentes datos
- Nodos que se usaran:
	- 4 nodos inject
		- El primer nodo mandara una cadena de texto.
		- Los tres nodos restantes mandaran un número entero, 0, 5 y 10.
	- 1 nodo dashboard text
	- 1 nodo dashboard gauge
	- 1 nodo dashboard chart
### Instrucciones
1. Crear y clonar un nuevo repositorio llamado Flow3
2. Ingresar a localhost:1880 y crear un nuevo flow
3. Agregar todos los nodos
4. Configurar los dashboards
	- Tiene que ser una pestaña que contenga un grupo para texto, y un grupo para gráficos
5. Configurar todos los nodos
6. Conectar los nodos de la siguiente forma
	- Inject de texto -> text
	- Inject 0, 5, 10 -> gauge y chart
7. Abrir el dashboard e ir seleccionando que valores se desean mandar, para poder verificar su funcionamiento
