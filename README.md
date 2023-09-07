# API Fibonacci en C#
Este proyecto es una API web desarrollada en C# utilizando ASP.NET Core que calcula los valores de la secuencia de Fibonacci para un índice dado. La secuencia de Fibonacci es una serie matemática donde cada número es la suma de los dos números anteriores, comenzando con 0 y 1. Por ejemplo, los primeros valores de la secuencia son 0, 1, 1, 2, 3, 5, 8, 13, y así sucesivamente.

Uso
Endpoint
La API expone un único endpoint para calcular el valor de Fibonacci en un índice específico:

GET /api/fibonacci/{n}
Donde {n} es el índice en la secuencia de Fibonacci que deseas calcular.

Ejemplos de Uso
Calcular Fibonacci en el índice 3:
GET /api/fibonacci/3
Respuesta: 2
Esto significa que el valor de Fibonacci en el índice 3 es 2, ya que la secuencia comienza con 0, 1, y luego 2.

Calcular Fibonacci en el índice 6:
GET /api/fibonacci/6
Respuesta: 8
En este caso, el valor de Fibonacci en el índice 6 es 8, ya que la secuencia continúa 0, 1, 1, 2, 3, 5, y finalmente 8.

Requisitos
Para utilizar esta API y ejecutar el proyecto en tu máquina, necesitas:

Visual Studio o cualquier otro IDE de C#.
ASP.NET Core instalado en tu máquina.
Configuración del Proyecto
Para configurar y ejecutar el proyecto en tu máquina, sigue estos pasos:

Clona este repositorio en tu máquina local.

Abre el proyecto en tu IDE de C#.

Ejecuta la aplicación para iniciar el servidor local.

Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar o expandir esta API Fibonacci, siéntete libre de abrir un problema o enviar una solicitud de extracción. Esto podría incluir la adición de características adicionales, pruebas unitarias o mejoras en la documentación.
