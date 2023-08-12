### Esquemas y Objetos:
	Agrupan objetos de la base de datos.
   el nombre completo de un objeto es Servidor.BaseDeDatos.Esquema.
   El Servidor es el dueño de la maquina.

### 3 TYPES OF SCHEMAS
- CONCEPTUAL:  high level overview of what your db will contain, how data will be organized, It is created in the initial project stage.

- LOGICAL: defines all the elements within the db and any related information, such as field names, entity relationships, integrity constrains and table names.

- PHYSICAL: combines contextual and logical information while adding technical requerements, It contains the syntax needed to create data structures within the disk storage.

### TEMPORARY TABLES

- Local: visible while the connectino/session is active, we put # in front of the name to create it.
- Global: we use ## infront of the name, these tables can be accessed by all other sessions.

