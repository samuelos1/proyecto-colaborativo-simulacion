# Modelo Híbrido para el Proyecto de Monitor de Actividad de Protocolos de Red

## 1. Introducción
Para optimizar la gestión del proyecto, hemos decidido combinar dos metodologías: **Scrum** y **Cascada (Waterfall)**.  
El objetivo es aprovechar la planificación estructurada de Cascada y la flexibilidad e iteraciones de Scrum.

---

## 2. Justificación de la elección
- **Cascada:** aporta un esquema secuencial, ideal para definir claramente la arquitectura del proyecto y los requerimientos técnicos del monitor.
- **Scrum:** permite iterar en el desarrollo, agregar mejoras y recibir retroalimentación continua durante la implementación del servicio, la aplicación y la interfaz web.

---

## 3. Cómo se aplicarán las metodologías

### 3.1 Fases de Cascada
1. **Planificación:** definir requerimientos completos del monitor, captura de datos y base de datos.
2. **Diseño:** crear el modelo de almacenamiento en MySQL y diseñar la interfaz web.
3. **Implementación:** desarrollo del servicio de Windows, aplicación de captura y sistema de colores para protocolos.
4. **Pruebas:** verificar la captura de datos, la clasificación de servicios y el reporteo de actividad.

### 3.2 Iteraciones de Scrum
- Cada fase del desarrollo se divide en **sprints de 1 semana**:
  1. Sprint 1: Captura de datos y validaciones IP/MAC.
  2. Sprint 2: Desarrollo de modelo de base de datos y aplicación de captura.
  3. Sprint 3: Interfaz web y sistema de colores para protocolos.
  4. Sprint 4: Reporteo gráfico de protocolos y ajustes finales.
- Roles:
  - **Product Owner:** define prioridades de funcionalidades.
  - **Scrum Master:** supervisa el progreso de los sprints.
  - **Equipo de desarrollo:** implementa y prueba las funcionalidades.

---

## 4. Beneficios del modelo híbrido
- Claridad en la planificación gracias a Cascada.  
- Flexibilidad y adaptabilidad gracias a Scrum.  
- Permite entregar incrementos funcionales mientras se mantiene una estructura organizada del proyecto.

---

## 5. Entregables
- Documento de requerimientos y diseño (Cascada).  
- Aplicación de captura y servicio Windows (Scrum).  
- Interfaz web funcional y reporteador (Scrum).  
- Documentación final del proyecto (Cascada + Scrum).

---

## 6. Tiempos estimados
| Fase / Sprint | Duración Estimada |
|---------------|-----------------|
| Planificación | 1 semana        |
| Diseño        | 1 semana        |
| Sprint 1      | 1 semana        |
| Sprint 2      | 1 semana        |
| Sprint 3      | 1 semana        |
| Sprint 4      | 1 semana        |
| Pruebas finales | 1 semana      |
