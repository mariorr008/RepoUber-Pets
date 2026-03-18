#  Descripcion del problema
### Nombre del proyecto : Uber mascotas 🐶

### Descripcion general:
En la aplicacion  de uber la mayoria de los conductores no permiten que se transporten animales durante los viajes lo cual se a convertido en una problematica , deseamos desarrollar una aplicacion movil de viajes donde se permita transportar mascotas .

### Objetivo general:
Desarrollar y facilitar los transportes para las personas que necesiten o deseen viajar con sus mascotas .

## Objetivos especificos :
- Facilitar el transporte de mascotas
- Brindar un buen servicio a las personas con mascotas

### Skateholders: 
- Inversores
- Personas que deseen trasnportarse con sus mascotas
- Conductores dispuestos a transportar mascotas en sus vehiculos
___

#  Marco de trabajo 
## Roles de SCRUM:
- Product Owner: Santiago Mendoza
- Scrum Master: Juan Pablo Navas
- Developers: Daniel Fernando Vargas , Mario Alberto Rojas 

## Artefactos SCRUM:
- Product Backlog
- Sprint Backlog 
- Incremento

#  Backlog 

## Lista de deseos :

### MENU DE REGISTRO ( USUARIO - CONDUCTOR )

### Registro de usuarios

    Nombre
    Numero de documento
    Correo electronico
    Nacionalidad / numero de telefono
    Mascota (Raza)


### Registro de conductores

    Nombre
    Numero de documento ( validar mayoria de edad )
    Validar licencia de conduccion
    correo electronico
    Nacionalidad / numero de telefono
    foto de perfil obligatoria
    Registro de vehiculo (placa,color,modelo,año del vehiculo)

### SISTEMA DE PAGOS DE VIAJES 

### Tipos de pago

    Efectivo
    Nequi
    Tarjetas moviles


### SISTEMA DE MAPA - UBICACIONES

    Recibir los servicios cercanos 
    Numero de documento ( validar mayoria de edad )

### SERVICIOS

    Chat entre usuario y conductor 
    Codigo por cada viaje 
    Calculo de total x distancia del viaje 
    Total de personas x viaje
    Total de mascotas ( depende del valor de personas )
    Multa al usuario x cancelacion de servicio
    Multa al conductor x cancelacion de servicio
    Calificacion de servicios 
    Recomendacion de conductores x calificacion

### SERVIDORES 
    Conexion con servidores
    Instalacion del servidor
    Licencia del servidor
    Sistema de actualizaciones 

### FRONTEND
### Parte visual de la aplicacion 
    Modulo 1
    Modulo 2 
    Modulo 3
    Modulo 4
    Modulo 5
    Conexion del frontend con el backend



### OTROS 

    Perfil editable de usuario
    Perfil editable de conductor
    Historial de viajes
    Sistema de notificaciones
    Sistema de soporte

## Product backlog    
**Primer sprint**
|ID|Historia de usuario|Prioridad|Estado|
|--|-------------------|---------|------|
|1|Registro Usuario|Media|En proceso|
|2|Registro Conductor|Media|En proceso|


## Historia de usuario:
---
**ID :** 1

**Nombre :** Registro usuario

**Como :** Usuario

**Quiero :** Registrarme en la app

**Para :** Acceder a los servicios de la app

**Criterios de aceptacion:**
- Dado que el usuario este en la pantalla de registro como usuario 
- El usuario ingresa sus datos correctamente
- El sistema crea su cuenta como usuario

**Reglas de la aplicacion:**
- El correo sera unico por cada cuenta
- La contraseña debe contar con numeros y simbolos

---

**ID :** 2

**Nombre :** Registro conductor

**Como :** Usuario conductor

**Quiero :** Registrarme en la app como conductor

**Para :** Acceder a los servicios como conductor de la app

**Criterios de aceptacion:**
- Dado que el usuario este en la pantalla de registro como conductor
- El usuario ingresa sus datos correctamente
- El sistema crea su cuenta como conductor

**Reglas de la aplicacion:**
- El correo sera unico por cada cuenta
- La contraseña debe contar con numeros y simbolos
- El conductor debe ingresar otros tipos de datos para su registro

---

## Sprint 
**Sprint N°:** 1

**Objetivo:** Implementar los registros de los dos tipos de usuarios habiles ( usuario , conductor )

**Historias seleccionadas:**

|ID|Tarea|Prioridad|
|--|-----|---------|
|1|Registro de usuarios|Media|
|2|Registro de conductores|Media|

**Tareas**

|Historia|Tarea|Responsable|
|--|-----|---------|
|1|Agregar usuario|Mario Rojas|
|1|Actualizar usuario|Mario Rojas|
|1|Eliminar usuario|Mario Rojas|
|1|Listar usuario|Mario Rojas|
|2|Agregar conductor|Daniel Vargas|
|2|Actualizar conductor|Daniel Vargas|
|2|Eliminar conductor|Daniel Vargas|
|2|Listar conductor|Daniel Vargas|