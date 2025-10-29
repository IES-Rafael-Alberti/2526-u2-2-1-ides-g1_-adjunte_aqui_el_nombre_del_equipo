# Punto 5: Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE

## IDE utilizado
- **IDE:** IntelliJ IDEA Ultimate - Versión 2025.2.4

## Descripción de la tarea
Programa "cuenta atrás" que cuenta de 10 a 0 y luego imprime "¡Despegue!"

### Lenguajes utilizados
- **Lenguaje 1:** Java
- **Lenguaje 2:** Kotlin

## Código implementado

### Lenguaje 1: Java
```java
public class Despegue {
    public static void main(String[] args) 
    
        for (int i = 10; i >= 0; i--) {
            System.out.println(i);
        }
        
        System.out.print("¡Despegue!");
    }
}
```

### Lenguaje 2: Kotlin
```kotlin
fun main(){
    for (i in 1..10){
        println(i)
    }
    print("¡Despegue!")
}
```

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Cuál fue el proceso para ejecutar el mismo programa en diferentes lenguajes dentro del mismo IDE?

IntelliJ IDEA ayuda mucho porque está diseñado para entender tanto Java como Kotlin

1. Colocar archivos: Pones el archivo Despegue.java en la carpeta src/main/java y el archivo Despegue.kt en la carpeta src/main/kotlin

2. Darle al "Play": El IDE reconoce automáticamente que ambos archivos son programas ejecutables (porque tienen una función **main**)

### Pregunta 2: ¿Qué diferencias encontraste en la generación del ejecutable entre los dos lenguajes?

La diferencia principal es el tamaño y las dependencias.

Ambos lenguajes se compilan a *bytecode*, que es lo que entiende la **Máquina Virtual de Java** (JVM).

El archivo ejecutable de Java (`.jar`) que se genera es muy pequeño. Sin embargo, el código de Kotlin depende siempre de un archivo extra llamado "Biblioteca Estándar de Kotlin"

## Evidencias
![Ejecución en Kotlin](<capturas/despegue kt.png>)
![Ejecución en Java](<capturas/despegue java.png>)