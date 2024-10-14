# Diagrama de flujo para aplicación de gym:
Inicio de sesión (Login):

Inicio → Usuario ingresa su nombre de usuario y contraseña.
Verificar credenciales en la base de datos (MySQL).
Si las credenciales son correctas, continuar.
Si las credenciales son incorrectas, mostrar error y reintentar.
Ingreso de rutina de gym:

Formulario de ingreso de rutina: El usuario ingresa datos sobre los ejercicios, repeticiones, series, etc.
Guardar rutina en la base de datos (MySQL):
Si el guardado es exitoso, mostrar mensaje de éxito.
Si hay un error, mostrar error y permitir reintentar.
Generador de gráficos de progreso:

Obtener datos del progreso desde la base de datos (MySQL).
Generar gráficos usando las librerías de Python (ej. Matplotlib, Seaborn).
Si los datos son correctos, mostrar gráficos.
Si hay un error en los datos o gráficos, mostrar mensaje de error.
Control de tiempo:

El sistema puede registrar la hora de inicio y fin de las rutinas para hacer seguimiento del tiempo dedicado a cada sesión.
Cierre de sesión:

Cerrar sesión o cerrar aplicación.
