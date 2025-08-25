# Proyecto de Tesis: Robot Wall-E para Recolección Autónoma de Basura

## Resumen
Este proyecto consiste en el diseño, desarrollo y prueba de un robot autónomo inspirado en Wall-E, capaz de recolectar basura utilizando una cámara ESP32-CAM, un electroimán, y sensores de proximidad. El robot incorpora comunicación WiFi mediante Raspberry Pi Pico 2 W para control y monitoreo remoto, y está diseñado para acoplarse mecánicamente con otro robot similar, permitiendo trabajo colaborativo.

---

## Índice
1. [Introducción](#introducción)  
2. [Objetivos](#objetivos)  
3. [Marco Teórico](#marco-teórico)  
4. [Metodología](#metodología)  
5. [Diseño y Desarrollo](#diseño-y-desarrollo)  
6. [Resultados](#resultados)  
7. [Conclusiones](#conclusiones)  
8. [Trabajo Futuro](#trabajo-futuro)  
9. [Referencias](#referencias)  
10. [Anexos](#anexos)  

---

## Introducción
La gestión de residuos es un desafío ambiental crucial. Este proyecto propone un robot autónomo que, mediante la integración de tecnologías de visión con la cámara ESP32-CAM, electromagnetismo y comunicación inalámbrica basada en Raspberry Pi Pico 2 W, puede recolectar basura de manera eficiente. La colaboración entre dos robots aumenta la capacidad operativa y mejora la cobertura del área de limpieza.

## Objetivos

### Objetivo General
- Diseñar y construir un robot estilo Wall-E capaz de recolectar basura de forma autónoma utilizando sensores y comunicación inalámbrica, con capacidad de acoplamiento mecánico con otro robot similar.

### Objetivos Específicos
- Implementar un sistema de visión para la detección de basura mediante la cámara ESP32-CAM.
- Integrar un electroimán para la recolección de objetos metálicos.
- Incorporar sensores de proximidad para evitar obstáculos y mejorar la navegación.
- Establecer comunicación WiFi utilizando Raspberry Pi Pico 2 W para control remoto y sincronización entre robots.
- Diseñar un mecanismo para el acoplamiento mecánico entre dos robots.

## Marco Teórico
- **Robótica Autónoma:** Principios básicos y aplicaciones en recolección de residuos.
- **Sensores y Actuadores:** Uso de cámaras (ESP32-CAM), sensores de proximidad y electroimanes.
- **Microcontroladores:** Capacidades y uso de Raspberry Pi Pico 2 W para control y comunicación.
- **Comunicación Inalámbrica:** Protocolos WiFi para control y sincronización.
- **Sistemas Mecánicos de Acoplamiento:** Diseño y funcionamiento.

## Metodología
- Investigación y selección de componentes electrónicos y mecánicos, enfocándose en ESP32-CAM y Raspberry Pi Pico 2 W.
- Diseño CAD del robot y sistema de acoplamiento.
- Desarrollo del software de control, procesamiento de imágenes y comunicación.
- Integración y pruebas funcionales.
- Evaluación de desempeño en escenarios simulados.

## Diseño y Desarrollo

### Componentes Principales
- **ESP32-CAM:** Cámara integrada para detección visual de basura con capacidades de procesamiento de imágenes.
- **Raspberry Pi Pico 2 W:** Microcontrolador con WiFi integrado para control y comunicación entre robots.
- **Electroimán:** Para atracción y recolección de objetos metálicos.
- **Sensor de Proximidad:** Evitar colisiones y mejorar navegación.
- **Sistema Mecánico de Acoplamiento:** Permite conexión física con otro robot.

### Diagrama del Sistema
![Diagrama del sistema](ruta/a/tu/imagen.png)

### Software
- Procesamiento de imagen en ESP32-CAM para detección de basura.
- Control de actuadores y navegación mediante Raspberry Pi Pico 2 W.
- Comunicación WiFi entre robots para sincronización y control remoto.

## Resultados
- Implementación funcional del robot con detección y recolección mediante ESP32-CAM y electroimán.
- Comunicación estable y control mediante Raspberry Pi Pico 2 W.
- Pruebas exitosas de acoplamiento mecánico y trabajo en equipo entre dos robots.

## Conclusiones
El desarrollo del robot Wall-E autónomo con ESP32-CAM y Raspberry Pi Pico 2 W demostró la viabilidad de integrar tecnologías de visión, control y comunicación para tareas de recolección de basura. El acoplamiento mecánico entre robots aumenta la eficiencia operativa.

## Trabajo Futuro
- Optimización del algoritmo de visión en ESP32-CAM para mayor precisión.
- Desarrollo de navegación avanzada y mapeo con Raspberry Pi Pico 2 W.
- Escalabilidad para múltiples robots en red WiFi.
- Incorporación de fuentes de energía renovable para mayor autonomía.

## Referencias
- [Referencia 1: Libro/Artículo]
- [Referencia 2: Página Web]
- [Referencia 3: Manual Técnico]

## Anexos
- Código fuente relevante
- Esquemas eléctricos
- Planos mecánicos
- Resultados de pruebas detallados

---

**Autor:** Tu Nombre  
**Fecha:** Agosto 2025  
**Institución:** Nombre de tu universidad o institución

---

*Este proyecto está bajo licencia MIT. Consulta el archivo LICENSE para más detalles.*

