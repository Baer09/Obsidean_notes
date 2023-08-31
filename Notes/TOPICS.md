### Esquemas y Objetos:
	Agrupan objetos de la base de datos.
   el nombre completo de un objeto es Servidor.BaseDeDatos.Esquema.
   El Servidor es el dueño de la maquina.

### SCHEMA 
	It helps to store objects (talbes, DB, Etc) and organized and separate them from the      others.
### 3 TYPES OF SCHEMAS
- CONCEPTUAL:  high level overview of what your db will contain, how data will be organized, It is created in the initial project stage.

- LOGICAL: defines all the elements within the db and any related information, such as field names, entity relationships, integrity constrains and table names.

- PHYSICAL: combines contextual and logical information while adding technical requerements, It contains the syntax needed to create data structures within the disk storage.

### TEMPORARY TABLES

- Local: visible while the connectino/session is active, we put # in front of the name to create it.
- Global: we use ## in front of the name, these tables can be accessed by all other sessions.

### ISO
International Organization for Standardization

### Principio del privilegio minimo : Hace referencia a un concepto de serguridad de la informacion en que se da a un usuario los niveles (Permisos )minimos necesrios para desempenar sus funciones laborales.

- Entidades de seguridad: Son entidades que  pueden solicitar  recursos de SQL server.

- Rol de niveles de servidor: podemos asignar roles para niveles de accesso a usuarios.

- sysadmin: users with this role can perform any activity in the server.  
- serveradmin: Can change server-wide configuration options and shut down the server.
- securityadmin: Manage log ins and their properties, they can GRANT, DENY and REVOKE server level permissions.
- dbcreator: can create, alter, drop and restore any database.



- Roles fijos de basesd de datas: 

- db_owner: can make all configurations

-  db_dbladmin: pueden ejecutar cualquier comando del lenguaje de definición de datos (DDL) en una base de datos

- db_datawriter: pueden agregar, eliminar o cambiar datos en todas las tablas de usuario.

- db_datareader: pueden leer todos los datos de todas las tablas y vistas de usuario

- db_denydatawriter: no pueden agregar, modificar ni eliminar datos de las tablas de usuario de una base de datos.

- db_denydatareader: no pueden leer datos de las tablas y vistas de usuario dentro de una base de datos.
