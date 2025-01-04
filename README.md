# Proyecto de práctica 2: Casos de prueba y clases de equivalencia para una aplicación de transporte - Urban Routes

## Descripción del Proyecto:

Este proyecto se centra en la identificación de clases de equivalencia y el diseno de casos de prueba, basandose en los Requisitos del Aplicativo de Urban Routes.

Urban Routes es una aplicación que crea rutas y calcula la duración y precio del viaje para diferentes tipos de transporte. Contiene dos campos para las direcciones: "Desde" y "Hasta". Además, cuenta con tres modos ("Óptimo", "Flash" y "Personal"), así como íconos para los tipos de transporte (automóvil del usuario, a pie, taxi, bicicleta, scooter o compartir un automóvil). Una vez el usuario establece sus ubicaciones "Desde" y "Hasta", la aplicación recibe esa información como puntos "A" y "B". Luego, calcula la duración total de viaje y el precio utilizando un algoritmo específico.

## Instrucciones para el Desarrollo del Proyecto: 

La tarea es analizar y descomponer los requisitos, dividir en clases de equivalencia y diseñar casos de prueba, para ello:

1. Dibuja un mapa mental para la función "Agregar licencia de conducir"
2. Define las clases de equivalencia y los valores límite para los campos de entrada "Nombre" y "Apellido" en el formulario Licencia de conducir
3. Dibuja un diagrama de flujo para calcular el precio y la duración de compartir un automóvil
4. Diseña pruebas para el cálculo del precio y la duración de compartir un automóvil

## Dato adicional: 

1. Para calcular los valores de la prueba a partir de las fórmulas, necesitarás los valores de velocidad. Estos datos están en la tabla que muestra la dependencia de la velocidad a la hora de inicio del viaje
   
2. Estudia dos fórmulas que se utilizan para calcular la duración y el precio:
                                                                             **T (duración del viaje) = S (distancia) / V (velocidad a la hora de salida)**
                                                                              **Costo = T (duración del viaje) * precio por minuto**

## Referencias - Se adjunta captura de pantalla: 

1. Adjunta mapa del aplicativo
2. Adjunta formato "Agregar licencia de conducir"
3. Cuadro Velocidad media del Automovil

## Desarrollo del Proyecto:

1. Analice minuciosamente los requisitos y los diseños para la función "Agregar licencia de conducir" plasmandolos de manera gráfica en un mapa mental.
   
2. **Dibuje el mapa mental** solo para el campo "Agregar licencia de conducir" y la ventana emergente correspondiente. No se incluyo otras partes del navegador a solicitud del proyecto. Considerando que el mapa mental lo dividi en dos partes: interfaz (cómo debería verse cada elemento) y funcionalidad. (cómo deberían comportarselas entradas de datos como usuario). De igual forma se adicionaron algunas zonas grises.
   
3. **Identifique las clases de equivalencia. y  defini los valores límite de cada clase.**

4. Elegi los valores de prueba para comprobar cada clase y sus límites, para los dos campos: "Nombre" y "Apellido"

5. **Disene el diagrama de flujo** solo en base a la velocidad del automóvil compartido en función de la hora de salida
   
6. Comprobe que el precio y la duración del viaje se calculen correctamente. Analice los requisitos para calcular la duración y el precio de compartir un automóvil en base a la tabla de Velocidad del automovil

7. Comprobe la logica del cálculo en base a velocidad y hora, y a las clases de equivalencia desarrolladas previamente.
   
9. Elegi valores de prueba para comprobar cada clase y sus límites en base a las fórmulas y el diagrama de flujo.
    
11. **Desarrolle Casos de prueba** basados en los valores de prueba dentro de las clases de equivalencia para comprobar que la lógica de cálculo de la duración y el precio de un viaje sea la correcta


   
