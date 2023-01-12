# **SEMANA 1**  

## **IDE, Visual Code y GitHub**

## **Visual Studio Code**

    1) JDK
    2) Extension Pack for Java
    3) Project Manager for Java

## **ATAJOS DEL VISUAL STUDIO CODE**

1. Command Palette  
    **Windows:** CTRL+SHIFT+P
2. Quick Open  
    **Windows:** CTRL+P
3. Toggle Sidebar  
    **Windows:** CTRL+B
4. Multi-Selector Cursor  
    **Windows:** CTRL+D
5. Copy Line  
    **Windows:** CTRL+ALT+UO or SHIFT+ALT+DOWN
6. Comment Code BLock  
    **Windows:** SHIFT+ALT+A(M.line) or CTRL+K+C(S.line)
7. Go back/ move forward  
    **Windows:** ALT+_> or +->
8. Show All Symbols  
    **Windows:** Ctrl+T
9. Tigger suggestion and Trigger parameter hints  
    **Windows:** Ctrl+SPACE, Ctrl+Shift+Space


## *GIT HUB*

Para crear nuestro primer proyecto, utilizaremos el atajo de teclado "ctrl + shift + p", seleccionaremos la opción "java proyect" y utilizaremos "too" ya que es un proyecto de prueba para Java, no un proyecto de empresa. Antes de cada práctica, es necesario configurar algunos aspectos en el terminal, como la instalación del entorno de trabajo JDK o verificar versiones de Java. También utilizaremos Git para configurar nuestros proyectos en la nube, descargando Git Bash y utilizando comandos para confirmar su instalación y verificar la versión correcta. Si es necesario, también configuraremos nuestro nombre de usuario y correo electrónico en Git mediante los comandos "git config user.name" y "git config user.email". En caso de no aparecer nuestra información, usaremos los comandos "git config --global user.name 'nuestro usuario'" y "git config --global user.email 'nuestro email'" para establecerla.




# Proceso de ejecución de un programa en Java

El nombre del archivo debe coincidir con el nombre de la clase y estar en mayúsculas.

1. **Código:** Es escrito por los programadores
2. **Compilación:** El proceso de compilación genera un código intermedio llamado Bytcode
3. **Bytecode:** Son instrucciones para la java Virtual Machine
4. **JVM:** La java Virtual Machine interpreta el bytecode generado
5. **Multiplataforma:** El código bytecode se puede ejecutar en diferentes sistemas operativos

**Developer**: El creador del programa  
**java**: Lenguaje de programación
***Compilador***: Herramienta encargada de analizar el código sintácticamente y semanticamente, e interpretarlo

La virtual machine genera un archivo con extensión `.class` que contiene el bytecode. En cambio, el sistema operativo genera un archivo con extensión `.exe`. Esto permite la ejecución de un mismo código en diferentes sistemas operativos, como Windows, Linux y Mac, logrando así la característica de multiplataforma.

# **SEMANA 2**

### **Algoritmia**

1. Algoritmo:
  * Pseudocodigo
  *  Diadramas de flujo -> figuritas
* Codigo (debugging)
* Traza(trace) -> Debug : Para saber si esta bien configurado, las salidas del programa.
* Se genera la informacion en la Ram, ocupa un espacio de almacenamiento.
#####Pseudocódigo para calcular el área de un rectángulo:
```imprimir "Itroduzca una longitud en metros"
leer longuitud
imprimir "introduzca una anchura en metros"
leer ancho
asignar a areaRectangulo = largo * ancho
imprimir "El área es de " areaRectangulo "metros cuadrados"




Pseudocódigo para encontrar el mayor de tres números:
    imprimir "Ingrese el 1er valor: "
    leer a
    imprimir "Ingrese el 2do valor: "
    leer b
    imprimir "Ingrese el 3er valor: "
    leer c

    Si (a>b) y (a>c)
        imprimir "el mayor valor es: " a
        salir
    Si (b>a) y (b>c)
        imprimir "el mayor valor es: " b
    Si (c>a) y (c>b)
        imprimir "el mayor valor es: " c
```

# **SEMANA 3**

## **POO**

**1)ERROR:**  
1.- Logico: Division entre 0  
2.- Compilador: En tiempo de ejecucion  

* Sintactico  
* Semantico 

**2) ISSUE:** Tiene un defecto en el programa, no lo cierra pero lo hace ir mal.  
**3) BUG:** Vulberabilidad, se aprovecha de los **ISSUE**  

```
To se puede mejorar :v  
```

ctrl F5 /* para documentar

doble linea ctrl + D

Seleccionar cogidos, clic derecho, refactorizar, extract metod, ingresarNombre, se crea un metodo

% mood, residuo de las divisiones

**Casteo de datos**

Para poder convertir a diferente tipo de datos

```
Cast (int) i;  
Conversion int a = Integer.parse.Int("i");
```

