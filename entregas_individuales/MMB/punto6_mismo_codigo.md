# Punto 6: Generación de ejecutables con diferentes IDEs a partir del mismo código fuente

## IDEs utilizados
- **IDE 1:** Visual Studio Code - Versión 1.105.1 
- **IDE 2:** PyCharm - Versión 2025.2.4

## Descripción de la tarea
Programa "cuenta atrás" en Python que cuenta de 10 a 0 y luego imprime "¡Despegue!"

## Código implementado

```python
# Código Python del programa cuenta atrás
for i in range(10, -1, -1):
    print(i)

print("¡Despegue!")
```

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Qué diferencias encontraste al ejecutar el mismo código fuente en diferentes IDEs?
Las diferencias que he encontrado al ejecutar el programa en VS Code y en PyCharm son las siguientes: en PyCharm, en la generación de ejecutables entra en juego las herramientas integradas en el IDE como la gestión de intérpretes, entornos virtuales y configuraciones de ejecución. PyCharm permite crear y gestionar automáticamente entornos virtuales, lo cual facilita la portabilidad del código a otros sistemas. En VS Code el proceso de generar el ejecutable requiere más la intervención del programador, ya que hay que configurar el intérprete de Python, los entornos virtuales y las rutas de ejecución desde las extensiones o la configuración.

### Pregunta 2: ¿Cuál de los IDEs te pareció más cómodo o eficiente para ejecutar el código Python o el lenguaje que hayas elegido? ¿Por qué?
PyCharm me ha parecido mucho más cómodo, ya que en VS Code he tenido que instalar varias extensiones de Python para poder ejecutar el programa, debugearlo... Mientras que PyCharm integra herramientas automáticas para Python; autocompletado, resaltado de sintaxis y detección de errores del código.

## Evidencias
### Ejecución en VS Code
![Ejecución en VS Code](/entregas_individuales/MMB/capturas/punto_5_programa_python.png)

### Ejecución en PyCharm
![Ejecución en PyCharm](/entregas_individuales/MMB/capturas/punto_6_python_pycharm.png)


