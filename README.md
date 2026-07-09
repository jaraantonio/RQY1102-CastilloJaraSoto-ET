# Sistema de Gestión Administrativa - Edificio "El Mirador"

**Asignatura:** RQY1102-004D - Ingeniería de Software
**Grupo:** 1

## Integrantes y Roles

| Integrante | Rol |
|---|---|
| Antonella Castillo |  |
| Antonio Jara |  |
| Florencia Soto |  |

## Descripción del Problema

El edificio "El Mirador" cuenta con 160 departamentos (60 % propietarios, 40 % arrendatarios) y enfrenta deficiencias en la gestión de sus gastos comunes debido al uso de un sistema ineficiente; los procesos son, en general, manuales, lo que genera:

- Falta de cobros automatizados y seguimiento de morosidad.
- Falta de canales de comunicación efectivos con los residentes.
- Falta de transparencia al rendir cuentas, afectando la confianza de la comunidad.
- Morosidad recurrente que perjudica directamente el flujo de caja.

## Solución Propuesta

Desarrollar un sistema de información que modernice y automatice la gestión administrativa del edificio, reemplazando los procesos manuales por contrapartes digitales más eficientes y confiables. El sistema contempla **7 ámbitos funcionales**:

1. **Gestión de Usuarios y Acceso**
2. **Gestión de Residentes y Unidades**
3. **Gestión Financiera y Cobranza**
4. **Notificaciones y Comunicaciones**
5. **Solicitudes y Atención**
6. **Consultas y Visualización**
7. **Reportes y Análisis**

La arquitectura de nuestra propuesta se basa en la implementación de **microservicios** (MS_Core, MS_Finanzas, MS_Notificaciones), aplicando a nivel interno de cada uno el patrón **MVC (Modelo-Vista-Controlador)**, aplicando principios de alta cohesión y bajo acoplamiento.

## Prototipo de Alta Fidelidad

[Ver prototipo en Figma](https://red-shift-68373201.figma.site)