*Descripcion del Proyecto*


Este proyecto en Java implementa y compara dos metodos de interpolacion polinomial:

1.Diferencias Divididas de Newton: Construccion de la tabla de diferencias divididas y evaluacion del polinomio interpolador.

2.Polinomio de Lagrange: Evaluacion directa mediante polinomios base y productoria.

El objetivo es comprobar experimentalmente que ambos algoritmos entregan el mismo valor interpolado para un conjunto de nodos dado.


*Estructura del Proyecto*

src/

└── interpolacion/
    ├── InterpolacionNewton.java
    ├── InterpolacionLagrange.java
    └── Principales.java


Requisitos del Entorno

Java Development Kit (JDK)

IDE: IntelliJ IDEA, NetBeans, o ejecucion por linea de comandos.


*Instrucciones de Ejecucion*

Desde Linea de Comandos

1.Navegar a la carpeta src/.

2.Compilar las clases:

3.Ejecutar la clase principal: java interpolacion.Principales


*Ejemplo de Salida*

--- TABLA DE DIFERENCIAS DIVIDIDAS ---

x_i	f[x_i]	Orden 1	Orden 2	

---------------------------------------------------

1.00	2.0000	1.0000	0.8333	

2.00	3.0000	3.5000

4.00	10.0000	


--- RESULTADO DE LA INTERPOLACION ---

El valor estimado en x = 3.00 es P(3.00) = 5.6667


--- RESULTADO DE LAGRANGE ---

El valor estimado con Lagrange en x = 3.00 es P(3.00) = 5.6667
