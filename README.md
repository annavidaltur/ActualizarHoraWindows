# ActualizarHoraWindows
Cada vez que enciendo el portátil la fecha y hora están desconfiguradas porque se ha acabado la pila de reloj. Para cambiarla tendría que desmontarlo por completo así que he credo un script que actualiza la hora desde una api.

### Requisitos 📋
Tener cualquier versión de PHP instalado

### Crear tarea programada en Windows 10 ⚙️
Accedemos a la aplicación _Programador de tareas_ de Windows y creamos una tarea básica con las siguientes características:
* Trigger: cuando el dispositivo arranque
* Acción: ejecutar un programa
  
Agregamos la ruta del script cambiarhora.php y listo!

---
⌨️ con ❤️ por [annavidaltur](https://github.com/annavidaltur) 😊
