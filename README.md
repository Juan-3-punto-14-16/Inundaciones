# Inundaciones

## 1. Problema

### ¿Qué situación, necesidad o problema quieren atender?

Actualmente, en la Zona Metropolitana de Guadalajara no existe un sistema eficiente que informe en tiempo real a la población sobre las zonas afectadas por inundaciones ni que alerte oportunamente a las personas cuando se encuentran en áreas de riesgo. Las inundaciones son una de las amenazas más frecuentes en la Zona Metropolitana de Guadalajara. 
Sus causas principales son las tormentas de alta intensidad y duración, las cuales, dada la urbanización descontrolada, caracterizada por la modificación de cauces y el aumento de la extensión de superficies impermeables. Junto con la presencia de redes artificiales de conducción (como colectores) con capacidades limitadas de captación y evacuación, han provocado un incremento de la superficie inundable así como su frecuencia y severidad, lo que ha vuelto las inundaciones más peligrosas y recurrentes.
Durante el temporal de lluvias en la Zona Metropolitana de Guadalajara, se generan entre 15 y 30 tormentas capaces de producir inundaciones mayores, durante las cuales, se documentan entre 200 y 300 incidencias, como coches varados, vialidades colapsadas, pérdida de bienes materiales y patrimonio, e inclusive, la pérdida de vidas. 

---

## 2. Objetivo general y objetivos particulares

### Objetivo General

Desarrollar un sistema basado en nodos IoT y validación cruzada de datos para vialidades de alto riesgo de inundación en la ZMG con el fin de detectar niveles críticos de agua y emitir alertas automatizadas en tiempo real que notifiquen a los ciudadanos sobre las inundaciones inminentes.

### Objetivos Particulares

1. Diseñar la arquitectura técnica y estructural del sistema definiendo la interconexión exacta entre el hardware, el backend y la PWA.
2. Integrar los módulos físicos mediante el ensamblaje de los sensores y microcontroladores con conectividad a la red.
3. Desarrollar el software central del sistema abarcando el algoritmo de validación automatizada y la interfaz gráfica interactiva de la PWA para la emisión de alertas.
4. Evaluar el rendimiento y la fiabilidad del sistema mediante simulaciones de riesgo y pruebas de latencia en la transmisión de datos.


### ¿Qué resultado concreto quieren conseguir con el proyecto?

Mediante el desarrollo de un sistema de alerta en tiempo real, se resolvería la actual brecha de comunicación. Con advertencias tempranas y precisas, las personas ganarían un margen de tiempo crucial para tomar decisiones preventivas, cambiar sus rutas y proteger tanto sus bienes materiales como su propia vida.

---

## 3. Alcance

### ¿Qué sí contempla el proyecto?

- Implementación de nodos IoT en vialidades principales con antecedentes de inundaciones dentro del Área Metropolitana de Guadalajara. 
- Análisis, procesamiento y transmisión de los datos extraídos de los sensores, registros históricos y pronóstico del clima en tiempo real. 
- Desarrollo de aplicación que permita a los usuarios notificar puntos de inundación. 
- Validación de los reportes de los usuarios por densidad de reportes en un punto específico.
- Envío de alertas automatizadas sobre puntos inundados en tiempo real y avisos previos sobre posibles inundaciones.
- Implementación de un mapa interactivo e informativo.
- Implementación del módulo de autenticación.

---

## 4. Fuera de alcance

### ¿Qué cosas deliberadamente no realizará el proyecto?

- Predicción de inundaciones.
- Monitorear todos los puntos estratégicos en riesgo de inundación en la Área Metropolitana de Guadalajara 
- Evitar o mitigar inundaciones. 

---

## 5. MVP (Minimum Viable Product)

### ¿Cuál es la versión mínima del proyecto que permitiría demostrar que la propuesta funciona?

Se construirá un nodo IoT conformado por un microcontrolador (ESP32), un sensor de nivel de agua y conectividad GSM. Las lecturas físicas serán enviadas al servidor central, el cual procesa la información para detonar una alerta básica informando sobre la inundación. Aunque el diseño conceptual del producto final contempla el cruce de datos con APIs meteorológicas y reportes ciudadanos, la versión construida en esta etapa se limitará a probar la comunicación de extremo a extremo (Hardware - Servidor - Interfaz base).
