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

1. **Análisis de Requisitos:** Realicé un análisis detallado de los requisitos y diseños para la función "Agregar licencia de conducir", representándolos gráficamente en un mapa mental.
   
2. **Mapa mental:** Elaboré el mapa mental exclusivamente para el campo "Agregar licencia de conducir" y su ventana emergente, excluyendo otras partes del navegador según lo solicitado en el proyecto. El mapa se dividió en dos secciones: interfaz (diseño visual de los elementos) y funcionalidad (comportamiento de los campos de entrada). También se añadieron áreas de incertidumbre (zonas grises).
   
3. **Identificación de Clases de Equivalencia:** Determiné las clases de equivalencia y definí los valores límite de cada una.

4. **Selección de Valores de Prueba:** Elegí los valores de prueba para verificar las clases de equivalencia y sus límites, específicamente para los campos "Nombre" y "Apellido".

5. **Diagrama de Flujo:** Diseñé el diagrama de flujo enfocado en la velocidad del automóvil compartido según la hora de salida.
   
6. **Verificación de Cálculos:** Verifiqué que el precio y la duración del viaje se calcularan correctamente, analizando los requisitos y la tabla de velocidad del automóvil.

7. **Comprobación de la Lógica de Cálculo:** Comprobé la lógica del cálculo de la duración y el precio con base en la velocidad, la hora de salida y las clases de equivalencia desarrolladas previamente.
   
8. **Pruebas de Valores de Clase:** Seleccioné valores de prueba para validar las clases de equivalencia y sus límites según las fórmulas y el diagrama de flujo.
    
9. **Desarrollo de Casos de Prueba:** Creé casos de prueba utilizando los valores de prueba seleccionados para verificar que la lógica de cálculo de la duración y el precio del viaje fuera correcta.


## Herramientas utilizadas:

**JIRA** Para el diseno de casos de pruebas y la gestion de errores.

**Documentación de los requisitos** revisión y análisis de los requisitos proporcionados.

**Hojas de calculo** Google sheets.

# CONCLUSIÓN

En esta práctica de proyecto, me di cuenta que soy una apasionada por la detección de errores, pude profundizar mis habilidades como QA Engineer, utilizando herramientas como JIRA y Google Sheet para documentar errores. Siempre estoy en busca de nuevos desafios que me permitan seguir creciendo como QA Engineer. 

************


:sparkles: **GRACIAS** por visitar este proyecto. 

**MUCHAS ESTRELLITAS DE LUZ PARA TI** :star2::star2::star2::star2:

**Si tienes preguntas puedes contactarme en mi Linkedln. :point_right: www.linkedin.com/in/sandrarodriguez461428179**
