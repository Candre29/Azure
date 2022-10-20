# SQL Databases, SQL inyection

# Crear Base de datos SQL

1. Primero necesitamos un servidor de SQL (Motor)

SQL Servers 

![Untitled](SQL_Databases/Untitled.png)

![Untitled](SQL_Databases/Untitled%201.png)

1. SQL Database 

![Untitled](SQL_Databases/Untitled%202.png)

Las bases de datos de Azure no te van a dejar pasar si no tienes la IP subida

Private endpoint y luego a la base de datos

![Untitled](SQL_Databases/Untitled%203.png)

![Untitled](SQL_Databases/Untitled%204.png)

### Habilitar la auditoria

1. Crear un logAnalytics Workspace

![Untitled](SQL_Databases/Untitled%205.png)

### Subir datos

1. Query editor (preview)

![Untitled](SQL_Databases/Untitled%206.png)

```html
INSERT INTO new_table(
	id,
	nombre,
	correo,
	tarjeta,
	direccion, 
	telefono
) VALUES(
	1,
	'Andru',
	'aleph87@innovaccion.mx',
	'1234561789541236',
	'Mi calle',
	454545

)
```

### Data discovery and classification

![Untitled](SQL_Databases/Untitled%207.png)

![Untitled](SQL_Databases/Untitled%208.png)

- Dynamic Data Masking

![Untitled](SQL_Databases/Untitled%209.png)

- Ledger

Todas las transacciones a los datos se van a guardar (todas las queries)

- activar cifrado de datos
- microsoft defender for cloud

**Valor predeterminado de enmascaramiento**

![Untitled](SQL_Databases/Untitled%2010.png)

# SQL inyection

- sqlmap
    - Hace un mapeo de vulnerabilidades sql inyection

```bash
sqlmap -h #ayuda

sqlmap -u <URL> --tor 
```

**Sanitizar formularios PHP**