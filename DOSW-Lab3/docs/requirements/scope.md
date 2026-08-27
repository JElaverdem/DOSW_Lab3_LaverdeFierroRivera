## 1. Sistema

* Nombre del sistema: TechCup
* Objetivo: El sistema tiene como objetivo: ## 1. Sistema

* Nombre del sistema:
* Objetivo: El sistema tiene como objetivo: Automatizar y centralizar la gestión de los torneos de fútbol semestrales organizados para los programas de ingeniería, permitiendo el registro de equipos, la validación de estudiantes, el procesamiento de pagos de inscripción y la generación de reportes automáticos para la Decanatura.

## 2. Problema a resolver
La gestión tradicional de los torneos deportivos universitarios se realiza mediante procesos manuales o herramientas desconectadas. Esto genera errores en la validación de la condición de estudiante de los participantes, falta de trazabilidad en el recaudo  de la inscripción  y una alta dificultad para:los organizadores,la Decanatura obtengan información consolidada y la generación de reportes precisos en tiempo real.

## 3. Diagrama de Contexto

### 3.1 Diagrama

![Context Diagram](/DOSW-Lab3/docs/uml/Diagrama de Contexto.png)

### 3.2 Actores

| Actor / Rol                        |          Descripción              |
|------------------------------------|:---------------------------------:|
| Capitan                      | Cliente del sistema que es el estudiante encargado de registrar el equipo, inscribir a los integrantes y gestionar el pago de la tarifa de inscripción.   |
| Organizador                                   |  Administrador del torneo encargado de crear los campeonatos, validar inscripciones, gestionar estados y programar partidos.   |
| Estudiante                                   |  Jugador que integra un equipo inscrito y consulta los horarios, canchas y resultados de los encuentros.                                 |
| Decano                                   |    Autoridad institucional que recibe los reportes oficiales en formato JSON sobre las inscripciones y pagos de los torneos.                               |

### 3.3 Sistemas externos


| Sistema                            |                                    Descripción                                        |
|------------------------------------|:-------------------------------------------------------------------------------------:|
| PSE                           | Sistema de pagos externa encargada de procesar de forma segura las transacciones monetarias de las inscripciones.    |
|                                    |                                                                                       |

## 4. Alcance del sistema
   
### 4.1 Dentro del sistema
Funciones que el sistema sí realiza (Relacione al menos 4).
Creación de torneos.
Creación de equipos.
Pago de inscripciones.
Generar reportes de pagos.
Generar reportes de los equipos.


### 4.2 Fuera del sistema
Funciones que no realiza (Relacione al menos 3).
No procesa pagos en efectivo ni transacciones financieras físicas de forma directa.
No incluye el envío automatizado de notificaciones o alertas por correo electrónico/SMS a los jugadores.
No gestiona la premiación económica ni la logística de entrega física de trofeos.
No procesa pagos en efectivo ni transacciones financieras físicas de forma directa.
No incluye el envío automatizado de notificaciones o alertas por correo electrónico/SMS a los jugadores.
No gestiona la premiación económica ni la logística de entrega física de trofeos.
