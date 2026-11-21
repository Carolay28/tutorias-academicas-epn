# Sistema de Gestión de Tutorías Académicas Docentes

Prototipo web para agendar, reprogramar y cancelar los horarios de atención (tutorías) de los profesores de la Facultad de Ingeniería de Sistemas.

Proyecto de curso de **Ingeniería de Software I (ICCD512)**, Escuela Politécnica Nacional, periodo 2026-B. Grupo 1.

## Equipo

| Integrante | Rol |
|---|---|
| Carolay Pillajo | Líder de Proyecto y QA |
| Christopher Pulupa | Analista de Requerimientos y Documentación |
| Karina Cárdenas | Arquitecta y Desarrolladora Backend |
| Leticia Montenegro | Diseñadora UI/UX y Desarrolladora Frontend |

**Docente:** Ing. Marcos Raúl Córdova Bayas

## Objetivo

Permitir que estudiantes y docentes gestionen las tutorías de forma ordenada, evitando cruces de horario, reservas duplicadas y exceso de cupos, y dejando un historial consultable.

## Alcance del prototipo (MVP)

- Registro e inicio de sesión con perfiles diferenciados (administrador/gestor y usuario).
- Mantenimiento (CRUD) de docentes y horarios de atención.
- Validaciones: sin cruces de horario, sin reservas duplicadas y control de cupos.
- Historial de solicitudes (Pendiente, Aprobada, Finalizada, Cancelada) y reporte resumen de uso.

## Tecnologías

Por definir.

## Estructura del repositorio

```
/docs      Documentos del proyecto (acta, SRS, manual de usuario)
/src       Código fuente del sistema
/design    Mockups y diseño de la interfaz
```

## Cómo trabajamos

- La rama `main` siempre debe estar estable.
- Cada tarea se hace en su propia rama (por ejemplo `feature/login` o `docs/acta`).
- Los cambios entran a `main` mediante pull request, revisado por al menos otro integrante.
- Las tareas se organizan en el tablero del proyecto (pestaña **Projects**).
- Mensajes de commit claros y en español, por ejemplo: `Agrega formulario de horarios`.

## Estado del proyecto

En fase inicial: definición del proyecto, estudio del problema y alcance.
