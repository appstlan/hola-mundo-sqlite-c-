# hola-mundo-sqlite-c-
Ejemplo de conexión a base de datos SQLite con C#

Cadena de conexión a una base de datos SQLite existente:
var cnn = new SQLiteConnection( "Data Source=db.sqlite;Version=3;New=False;Compress=True;" );

Agrege la libreria System.Data.SQLite.DLL a las referencias del proyecto, desde el instalador de paquetes Nuget.


