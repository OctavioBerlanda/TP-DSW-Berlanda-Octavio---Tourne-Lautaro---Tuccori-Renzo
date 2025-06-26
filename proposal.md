# Propuesta TP DSW

## Grupo
### Integrantes
* 51638 - Berlanda, Octavio (Comisión 304)
* 50956 - Tourne, Lautaro (Comisión 304)
* 51308 - Tuccori, Renzo (Comisión 302)

### Repositorios (actuales)
* [Back End](https://github.com/RenTuccori/Trabajo-Dsw/tree/main/BackEnd)
* [Front End](https://github.com/RenTuccori/Trabajo-Dsw/tree/main/FrontEnd)

## Tema
### Descripción
Desarrollaremos una aplicación de turnos online para el sanatorio, diseñada para optimizar la gestión de citas médicas tanto para pacientes como para el personal del sanatorio. Esta plataforma facilitará la reserva de turnos de manera eficiente, brindando acceso a información relevante y mejorando la experiencia general del servicio de salud.

### DER
![Diagrama de Entidad Relacion](https://github.com/OctavioBerlanda/TP-DSW-Berlanda-Octavio---Tourne-Lautaro---Tuccori-Renzo/blob/main/DERturnosOnline.drawio.png)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Sede<br>2. CRUD Especialidad<br>3. CRUD Obra Social|
|CRUD dependiente|1. CRUD Turno {depende de} CRUD Persona y Medico<br>2. CRUD Combinación (Una sede, una especialidad y un doctor) {depende de} CRUD Sede, especialidad y doctor  |
|Listado<br>+<br>detalle| 1. Listado de medicos filtrado por especialidad, muestra nombre, apellido del medico <br> 2. Listado de turnos filtrado por rango de fechas, muestra fecha de turno, hora, especialidad y medicos|
|CUU/Epic|1. Crear un nuevo turno Paciente <br>2. Consultar turnos Medico |


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Persona<br>2. CRUD Medico<br>3. CRUD Turno<br>4. CRUD Especialidad<br>5. CRUD Obra Social<br>6.CRUD Sede|
|CUU/Epic|1. Listar turno<br>2. Confirmar turno<br>3. Cancelar turno<br>4. Recordatorio pór mail un dia antes|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de turnos pendientes a confirmacion, confirmados y asistidos <br>2. Listado de medicos filtrado por especialidad |

