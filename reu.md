## gracias a todos!!
## diseño de base de datos

* Base de datos común entre aplicaciones.
* Las aplicaciones tendrán permisos a Schemas distintos (ej, cobranzas, DPI, maquinaria, etc).
* El backend va a conectarse a la base de datos a través de un _connection pool_.
* Se usará JWT para evitar llamadas constantes a la base de datos.
