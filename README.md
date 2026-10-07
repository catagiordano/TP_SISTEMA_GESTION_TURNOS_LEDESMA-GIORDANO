# TP_SISTEMA_GESTION_TURNOS_LEDESMA-GIORDANO

# ETAPA 1 - IDEA DEL PROYECTO + DIAGRAMA DE CLASES: 
1. DESCRIPCION BREVE DEL SISTEMA:
El proyecto consiste en desarrollar un Sistema de Gestión de Turnos para un consultorio, su objetivo principal es permitir administrar de manera organizada los turnos de atención de los pacientes.
El sistema permitirá registrar y administrar información de pacientes, profesionales, especialidades y turnos. A través de una aplicación de escritorio desarrollada en Windows Forms, se podrán realizar operaciones de alta, baja, modificación y consulta de los datos.
Las principales entidades del sistema serán:
- Paciente: representa a la persona que solicita un turno.
- Profesional: representa al médico o profesional que brinda la atención.
- Especialidad: representa la especialidad médica del profesional.
- Turno: representa una reserva de atención entre un paciente y un profesional en una fecha y horario determinados.

2. OBJETIVOS Y FUNCIONALIDADES PREVISTAS:
Objetivos específicos:
Registrar y administrar los datos de los pacientes.
Registrar y administrar los profesionales del consultorio.
Administrar las especialidades médicas.
Crear y gestionar turnos asignando un paciente a un profesional.
Consultar los turnos registrados.
Evitar la asignación de dos turnos al mismo profesional en la misma fecha y horario.
Generar reportes que permitan obtener información útil sobre los turnos y las personas registradas.

3. FUNCIONALIDADES ABM:
ABM de Pacientes Permitirá:
Alta: registrar un nuevo paciente.
Baja: eliminar un paciente registrado.
Modificación: actualizar sus datos.
Consulta: visualizar y buscar pacientes registrados.
Datos posibles: IdPaciente - Nombre - Apellido - DNI - Teléfono - Email - Fecha de nacimiento

ABM de Profesionales Permitirá:
Alta: registrar un nuevo profesional.
Baja: eliminar un profesional.
Modificación: actualizar sus datos.
Consulta: visualizar profesionales registrados.
Datos posibles: IdProfesional - Nombre - Apellido - Matrícula - Teléfono - Email - Especialidad - Gestión de Turnos

Además el sistema permitirá gestionar los turnos:
Registrar un nuevo turno - Modificar fecha y/u horario - Cancelar un turno - Consultar turnos existentes
Datos principales: IdTurno - Fecha - Hora - Paciente - Profesional - Estado
Los estados serian, ejemplo:
Pendiente
Atendido
Cancelado

4. REPORTES:

Reporte 1 — Turnos del día: Mostrar todos los turnos correspondientes a una fecha determinada.
Información: Hora - Paciente - Profesional - Especialidad - Estado del turno

Reporte 2 — Turnos por profesional: Permitir seleccionar un profesional y consultar todos sus turnos dentro de un período determinado.

Reporte 3 — Turnos por especialidad: Mostrar la cantidad y/o listado de turnos correspondientes a cada especialidad médica.

Reporte 4 — Historial de turnos de un paciente: Permitir seleccionar un paciente y visualizar sus turnos anteriores y futuros, indicando:
Fecha- Hora - Profesional - Especialidad - Estado.























