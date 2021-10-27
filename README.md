# challenge_ikon
Reto de programación

Pasos a seguir
- Descargar archivo ikon_challenge_antonio.rar
-	Descomprimir carpeta del proyecto ikon_challenge_antonio.rar
-	Dentro de la carpeta del proyecto Ikon_challenge_antonio se encuentra el archivo App.config sección appSettings en él se encuentran 4 valores con los siguientes identificadores

ruta_in = Ruta de acceso al archivo challenge.in

ruta_out = Ruta de acceso al archivo challenge.out

nombre_in = Nombre del archivo de valores de entrada fijo callenge.in

nombre_out = Nombre del archivo de valores de salida fijo callenge.out

Opcional: cambiar los valores de ruta_in y ruta_out con los destinos deseados (Si se cambian los valores ruta_in ruta_out sera necesario compilar nuevamente el proyecto en release).
Opcional: Cambiar los valores de nombre_in y nombre_out

-	En la ruta ikon_challenge_antonio->bin->reléase->netcoreapp3.1, se encuentra el archivo ejecutable con nombre ikon_challenge_antonio.exe 
 
Obligatorio: Ejecutar la aplicación ikon_challenge_antonio.exe

Notas:	
-	Si los archivos no están creados el sistema creará estos documentos en los destinos asignados en ruta_in y ruta_out.  
-	Si el archivo challenge.in se encuentra vacío se realiza una precarga con los valores del ejemplo en el archivo challenge.in
-	Si existe algún problema de formato en el archivo challenge.in el sistema lo notificara.
-	Al finalizar el proceso de configuración de dispositivos sin errores el sistema indicara esto al usuario.
-	Los accesos a los archivos challenge.in/.out sera directo en la carpeta principal descargada por medio de rutas relativas.

