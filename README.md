# Vigilancia de Albic Cloud

Cada 5 minutos se comprueba que responden:

- la aplicación (app.albic.es) y su servidor;
- el repositorio de los DeCA;
- cloud.albic.es y la copia de contingencia de los DeCA;
- el campus (formacion.albic.es).

Si algo falla tres veces seguidas, se abre un aviso en **Issues** y GitHub lo manda por correo. Cuando todo vuelve a responder, el aviso se cierra solo.

Solo se consultan direcciones públicas: aquí no hay claves ni datos.
