📌 Aplicación de SCRUM al Proyecto “Monitor de Actividad de Protocolos de Red”
1. Descripción del Proyecto

El proyecto consiste en desarrollar un sistema que monitoree la actividad de protocolos de red en equipos dentro de una red empresarial.
El sistema debe capturar información como sistema operativo, hostname, IP, MAC, fabricante, fecha y hora; validar que IP y MAC no se repitan; almacenar datos en MySQL; ejecutar un servicio de Windows que arranque automáticamente; mostrar un ícono en system tray; contar con una aplicación de captura; una interfaz web responsiva; clasificación de protocolos seguros/inseguros; y un módulo de reportes gráficos.

2. Roles Scrum
Product Owner (PO)

Define los requisitos del proyecto.

Prioriza funcionalidades en el Product Backlog.

Mantiene la visión del producto.

Scrum Master (SM)

Facilita las ceremonias Scrum.

Elimina impedimentos del equipo.

Asegura que se sigan las prácticas ágiles.

Development Team

Responsables de:

Programar el servicio de Windows.

Crear el módulo de captura.

Implementar validaciones de IP/MAC.

Crear el modelo en MySQL.

Desarrollar backend y API.

Desarrollar interfaz web responsiva.

Construir reportes gráficos.

Clasificar protocolos seguros/inseguros.

3. Product Backlog
PB-01 — Módulo de captura

Captura SO, hostname, IP, MAC, fabricante, fecha y hora.

No repetir datos si el puerto ya fue usado en los últimos 10 minutos.

PB-02 — Validación de integridad

Validar que la IP y MAC no estén asignadas a otro hostname.

PB-03 — Modelo MySQL

Crear tablas:

Equipo

Fabricante

Protocolo

Protocolo_Usado

PB-04 — Servicio de Windows

Arranca con el sistema operativo.

Debe mantenerse siempre activo.

PB-05 — System Tray

Ícono permanente que no pueda ser cerrado manualmente.

PB-06 — Aplicación de captura (C# o VB)

Interfaz para capturar datos definidos en PB-01.

PB-07 — Interfaz web responsiva

Mostrar datos recabados.

Clasificación por colores:

Verde: seguro

Amarillo: intermedio

Rojo: inseguro

Naranja: innecesario/no recomendado

PB-08 — Clasificación de protocolos

Identificar protocolos necesarios e innecesarios.

PB-09 — Reportador gráfico

Gráficos circulares de:

Protocolos seguros

Protocolos inseguros

4. Plan de Sprints (2 semanas cada uno)
Sprint 1 — Arquitectura y Base de Datos (2 semanas)

Objetivos:

Definir arquitectura general.

Crear modelo de datos en MySQL.

Preparar repositorio y configuración inicial.

Entregables:

Documento de arquitectura.

Base de datos inicial funcional.

Sprint 2 — Captura y Validación (2 semanas)

Objetivos:

Crear módulo de captura.

Evitar capturas repetidas por 10 min.

Validar IP/MAC vs hostname.

Entregables:

Código funcional del módulo de captura.

Validaciones operativas.

Sprint 3 — Servicio Windows y App de Captura (2 semanas)

Objetivos:

Crear servicio que arranque con Windows.

Construir aplicación de captura en C#/VB.

Añadir ícono en system tray.

Entregables:

Servicio instalable.

Aplicación con UI mínima.

Sprint 4 — API y Almacenamiento en MySQL (2 semanas)

Objetivos:

API REST para enviar datos.

Guardar captura en MySQL.

Entregables:

Endpoints disponibles.

Pruebas de integración.

Sprint 5 — Interfaz Web Responsiva (2 semanas)

Objetivos:

Mostrar equipos monitoreados.

Interpretación visual por colores.

Entregables:

Dashboard inicial.

Vistas completas.

Sprint 6 — Reportes Gráficos (2 semanas)

Objetivos:

Gráficos circulares de protocolos seguros/inseguros.

Dashboard final.

Entregables:

Módulo de reportes.

Dashboard final con gráficas.

5. Cronograma del Proyecto (12 semanas)
Sprint	Duración	Enfoque
1	2 semanas	Arquitectura y BD
2	2 semanas	Captura y validación
3	2 semanas	Servicio y aplicación
4	2 semanas	API y almacenamiento
5	2 semanas	Interfaz web
6	2 semanas	Reportes gráficos
6. Entregables Finales

Servicio de Windows funcional.

Aplicación de captura.

API REST.

Interfaz web responsiva.

Reportador gráfico.

Base de datos completa.

Documentación técnica.

Documentación metodológica (este archivo).

7. Beneficios de aplicar Scrum en este proyecto

Permite avanzar de forma incremental sin esperar hasta el final.

Prioriza tareas según valor para el usuario.

Facilita la detección temprana de errores.

Organiza mejor el desarrollo en módulos.

Permite ajustes rápidos según avances.
