# Punto 5: Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE

## IDE utilizado
- **IDE:** Visual Studio Code - Versión 1.105.1 

## Descripción de la tarea
Programa "cuenta atrás" que cuenta de 10 a 0 y luego imprime "¡Despegue!"

### Lenguajes utilizados
- **Lenguaje 1:** Python
- **Lenguaje 2:** Java

## Código implementado

### Lenguaje 1: [Python]
```Python
for i in range(10, -1, -1):
    print(i)

print("¡Despegue!")
```

### Lenguaje 2: [Java]
```Java
public class Main {
    public static void main(String[] args) {
        for (int i = 10; i >= 0; i--) {
            System.out.println(i);
        }
        System.out.println("¡Despegue!");
    }
}
```

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Cuál fue el proceso para ejecutar el mismo programa en diferentes lenguajes dentro del mismo IDE?
Los he ejecutado en VS Code, primero he tenido que instalar las extensiones necesarias de cada lenguaje para que puedan ajecutarse. El intérprete de Python ha ejecutado el código directamente, mientras que en Java, elc ompilador javac ha compilado el código fuente, ha generado el bytecode y luego la Máquina Virtual de Java JVM ha interpretado/ejecutado ese bytecode.

### Pregunta 2: ¿Qué diferencias encontraste en la generación del ejecutable entre los dos lenguajes?
En Python, se ha ejecutado el programa directamente gracias al intérprete, mientras que en java, la generación del ejecutable consiste en lo siguiente: se compila el código fuente a bytecode y la Máquina Virtual de Java (JVM) ejecuta ese bytecode
Es muy beneficioso saber manejar diferentes lenguajes en un mismo entorno ya que permite aprovechar las características de cada lenguaje y centralizas las herramientas en un mismo entorno, sin necesidad de estar cambiando de IDE, además de que esto te amplía los proyectos en los que puedes trabajar, incluyendo los que necesitan varios lenguajes.

## Evidencias
### Ejecución en Python
![Ejecución Python](/entregas_individuales/MMB/capturas/punto_5_programa_python.png)

### Ejecución en Java
![Ejecución Java](/entregas_individuales/MMB/capturas/punto_5_programa_java.png)

