# Buenas Prácticas para el Desarrollo de Nuevos Proyectos:
===========================================================
```linux
1- Se crea el ambiente de producción.
2- Nada se prueba en el ambiente de producción solo se instalan módulos y se cargan maestros.
3- Se hace un respaldo cada 24h de producción.
4- Se hace una copia de producción todos los dias y se llama Demo.
5- Todas las pruebas de módulos se hacen en Demo.
6- Demo se eliminará todos los días, no cargar datos maestros en Demo.
7- No se desarrolla ni en Demo ni en Producción sino local.
8- Las pruebas que el un módulo funciona no se hacen local sino en Demo.
9- Todos los días es necesario revisar los ciclos de venta/compra para ver que ningun cambio que se agrego afecte a Odoo.
10- Al terminar todos los dias hacer push e informar en el grupo los avances del proyecto.
```
