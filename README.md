# sesion_05_lab01
Laboratorio Registros

# Enunciado del Ejercicio

- Crearemos u repositorio en GitHub con el nombre sesion_05_lab01
- Lo clonaremos en nuestor equipos
- Insertaremos el inventario y el ansible.cfg necesario para conectarnos a los nodos
- Creamos un playbook con el nombre "playbook.yml"
- Localizaremos un modulo que nos permita modificar la zona horaria de los nodos
- Desarrollaremos un play que lleve a cabo los siguiente cambios:
	- Miraremos la HORA (hora, minuto y segundo) actual y la guardaremos en un registro
	- Cambiar la zona horaria del nodo01 a Europe/Moscow y guardaremos los datos de salida en un registro
	- Crearemos un fichero en la ruta /tmp con el nombre datos_horarios_HOSTNAME.txt
	- Miraremos la HORA (hora, minuto y segundo) actual y la guardaremos en un registro
	- Dentro del fichero anterior deberemos de imprimir los siguientes frases:
		- La zona horaria antes del cambio es ZONA_HOARIA Y la hora era HORA
		- La zona horaria despues del cambio es ZONA_HOARIA Y la hora era HORA

- Volveremos a dejar la zona horaria como estaba antes de cambiarla (usar el registro anterior)
