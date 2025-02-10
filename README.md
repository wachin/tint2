# tint2
Panel tint2 personalizado de Washington Indacochea

# Lanzador de aplicaciones
En este panel el icono de la izquierda es xfce4-appfinder para ver las aplicaciones.

Y está en el archivo de configuración:

.config/tint2/tint2rc

como:

button_icon = /usr/share/icons/Papirus/48x48/apps/xfce4-appfinder.svg

# Cerrar sesión
Para cerrar sesión es el botón de la derecha abajo, el cual utiliza lxsession-logout 

Y está en el archivo de configuración:

.config/tint2/tint2rc

como:

button_icon = /usr/share/icons/Papirus-Light/24x24/panel/system-shutdown-panel-restart.svg

# El Relog, abreviación de tiempo
Por defecto la hora del relog me aparece ejemplo así:

lunes 10 febrero

y deseo que esté abreviado, para hacerlo dar clic a las configuraciones de tint2 y en la pestaña reloj, en formato de segunda línea dice:

%A %d %B

lo edito y lo dejo así:

%a %d %b

y la hora ahora me la muestra asj́i:

lun 10 feb

así lo deseo yo para tener más espacio en el panel