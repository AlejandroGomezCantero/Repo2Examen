# Repo2Examen

# 📖 Explicación clara y comprensible del proyecto  
Este proyecto consiste en una aplicación Java que permite a los pacientes reservar citas con médicos de un consultorio. Los pacientes podrán elegir una fecha y hora, y el sistema verificará la disponibilidad del médico antes de confirmar la cita. 
Además, el sistema permitirá a los médicos ver su agenda y modificar o cancelar citas si es necesario.

## 📂 Estructura adecuada con secciones bien definidas 

**Introducción**

Este proyecto es una aplicación de consola desarrollada en Java que permite a los pacientes reservar citas médicas con facilidad, mientras que a los médicos les facilita gestionar su agenda de manera eficiente. Los pacientes pueden seleccionar la fecha y hora que más les convenga, y el sistema verifica la disponibilidad de los médicos antes de confirmar la cita. También incluye funciones como la visualización de la agenda del médico y la gestión de citas pasadas, incluyendo su cancelación.

**Como Instalarlo**

1. *Clonamos el repositorio en la maquina local*  
   git clone https://github.com/AlejandroGomezCantero/Repo2Examen

 *![image](https://github.com/user-attachments/assets/bca18f12-e423-484e-81a9-08d5aed7a6f5)*


**USO**

*Agregar una tarea: *
add "Comprar pan"

*Listar tareas pendientes: *
list

*Eliminar una tarea: * 

remove tarea


### 🛠 Uso de Ramas en Git y gitignore


Rama1 - Cambios en Doctor y Paciente
En esta rama, se agregaron nuevos elementos en las clases Doctor.java y Paciente.java. Específicamente:

Se agregó un nuevo doctor a la clase Doctor.java. Este cambio permite que se pueda gestionar un nuevo doctor en el sistema, posiblemente con información como nombre, especialidad y contacto.

Se agregó un nuevo paciente a la clase Paciente.java. De manera similar al doctor, se añadieron datos relativos a un nuevo paciente, como nombre, edad y enfermedad.

Clases modificadas/añadidas:

Doctor.java

Paciente.java

Efecto en el proyecto:

Estos cambios permiten la incorporación de nuevos doctores y pacientes al sistema. Con ellos, el proyecto podrá gestionar citas médicas de manera más eficiente, permitiendo agregar diferentes doctores y pacientes al sistema para asignar citas o administrar su historial.

Rama2 - Cambios en Cita y HistóricoPacientes
En esta rama, se realizaron las siguientes modificaciones:

Se agregó una nueva clase llamada HistoricoPacientes.java, que puede ser útil para almacenar el historial de citas o enfermedades de los pacientes, lo que mejora la organización de la información.

Se agregó una nueva cita en la clase Cita.java, probablemente para gestionar las citas médicas de los pacientes con los doctores disponibles en el sistema.

Clases modificadas/añadidas:

HistoricoPacientes.java

Cita.java

Efecto en el proyecto:

La clase HistoricoPacientes.java permite almacenar y consultar el historial médico de cada paciente. Esto puede incluir detalles de citas previas, tratamientos, enfermedades pasadas, etc. La nueva cita en Cita.java añade la capacidad de gestionar nuevas citas médicas, lo que es fundamental para el flujo del sistema de gestión de pacientes.

Resumen de las ramas y su propósito:

Rama1: Mejora la gestión de los doctores y pacientes, permitiendo agregar nuevos elementos a cada uno para facilitar la asignación de citas.

Rama2: Introduce un sistema de historial de pacientes, además de mejorar la gestión de las citas médicas dentro del sistema.


 **Recursos Adicionales**

 *Como crear reposiorios: * https://www.atlassian.com/es/git/tutorials/setting-up-a-repository 
 *Crear ramas: * https://www.freecodecamp.org/espanol/news/explicacion-de-la-rama-de-gi-como-eliminar/
 *Guia sobre github: * https://docs.github.com/es/get-started/start-your-journey/hello-world
