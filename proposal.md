# Propuesta TP DSW

## Grupo
### Integrantes
* 51638 - Berlanda, Octavio (Comisión 304)
* 50956 - Tourne, Lautaro (Comisión 304)
* 51308 - Tuccori, Renzo (Comisión 302)

### Repositorios
* [Back End](https://github.com/RenTuccori/Trabajo-Dsw/tree/main/BackEnd)
* [Front End](https://github.com/RenTuccori/Trabajo-Dsw/tree/main/FrontEnd)
## Tema
### Descripción
Desarrollaremos una aplicación de turnos online para el sanatorio, diseñada para optimizar la gestión de citas médicas tanto para pacientes como para el personal del sanatorio. Esta plataforma facilitará la reserva de turnos de manera eficiente, brindando acceso a información relevante y mejorando la experiencia general del servicio de salud.

### DER
![Diagrama de Entidad Relacion](https://drive.google.com/file/d/122IO0ubhLDxhaA4X3e-sbBzIuYNGYRmf/view?usp=drive_link)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Medico<br>2. CRUD Persona<br>3. CRUD Obra Social|
|CRUD dependiente|1. CRUD Turno {depende de} CRUD Persona y Medico<br>2. CRUD Historial medico {depende de} CRUD Medico y Persona  |
|Listado<br>+<br>detalle| 1. Listado de medicos filtrado por especialidad, muestra nombre, apellido del medico <br> 2. Listado de turnos filtrado por rango de fechas, muestra fecha de turno, hora, especialidad y medicos|
|CUU/Epic|1. Crear un nuevo turno Paciente <br>2. Consultar turnos Medico |


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Persona<br>2. CRUD Medico<br>3. CRUD Turno<br>4. CRUD Especialidad<br>5. CRUD Obra Social<br>6. CRUD Evento<br>|
|CUU/Epic|1. Listar turno<br>2. Confirmar turno por mail<br>3. Cancelar turno<br>4. Recordatorio pór mail un dia antes|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de turnos pendientes a confirmacion, confirmados y asistidos <br>2. Listado de medicos filtrado por especialidad |
|CUU/Epic|1. Consultar especialidades mas concurridas en el mes <br>2. Consultar pacientes mas recurrentes |

