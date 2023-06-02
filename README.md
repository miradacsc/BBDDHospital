# Base de Datos requerida por el Hospital Regional Mindhub 

![Hospital](https://github.com/miradacsc/BBDDHospital/assets/74154572/f12bfd39-8c83-42d8-8f30-60361d38a5a2)

> Epica
>> Se requiere un sistema de gestión hospitalaria que facilite el registro de pacientes, incluyendo su nombre, edad y número de asociado de obra social. También se requiere llevar un registro de los médicos, incluyendo su nombre completo y especialidad. Además, el sistema debe permitir la asignación de médicos a los distintos turnos, especificando el horario de servicio correspondiente a cada turno.
>>> Historias de Usuario
>>>> Como usuario, Quiero un sistema, Para registrar a los pacientes. <br>
>>> Como usuario, Quiero un sistema, Para registrar a los médicos por especialidad. <br>
>>> Como usuario, Quiero un sistema, Para identificar el horario y fecha de los turnos.
>>>>> Casos de Prueba
>>>>>> Verificar que este cargado el Id del paciente <br>
>>>>>> Verificar que este cargado el Id del médico <br>
>>>>>> Validar eliminar un turno <br>
>>>>>> Consultar la fecha y hora de turnos <br>
>>>>>> Consultar medicos por especialidad <br>
>>>>>> Validar modificar numero de obra social <br>
>>>>>> Validar relación entre paciente, médico y turno <br>

### Requerimientos

- Tabla Pacientes (identificador, nombre paciente, edad, número de asociado obra social)
- Tabla Médico(identificador, nombre médico, especialidad)
- Tabla Turnos(identificador, paciente, médico, nota)

### EDR

![EDR](https://github.com/miradacsc/BBDDHospital/assets/74154572/ef4e01f2-eb1f-4766-b886-60838a72cb62)

Creación de tablas
-------------
![Tables_creation](https://github.com/miradacsc/BBDDHospital/assets/74154572/5a496fe7-2415-4542-aedd-250d22329520)

> INSERT Pacientes
![Insert Pacientes](https://github.com/miradacsc/BBDDHospital/assets/74154572/d985a87a-d4db-42b7-9500-befb25cc3dcd)

> INSERT Médicos
![Insert Medicos](https://github.com/miradacsc/BBDDHospital/assets/74154572/315900d3-512b-4c82-ade5-4888c42303fc)

> INSERT Turnos
![Insert Turnos](https://github.com/miradacsc/BBDDHospital/assets/74154572/41bbdd3c-5187-482d-9562-dbe59845aedb)
