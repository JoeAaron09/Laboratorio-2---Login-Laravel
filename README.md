# Laboratorio-2---Login-Laravel

Prerrequisitos:

- PHP versión 8.0 o superior

- Composer versión 2.9.5

- Laravel installer

- Paquete de WampServer

- Servidor Web: Apache

- Base de Datos: MySQL

- Editor de código: Visual Studio Code

- NPM versión 11.12.1

- Sistema Operativo: Windows

Instalación de Dependencias:

En la siguiente sección agrego algunas capturas del proceso de instalación. Honestamente, no tomé muchas porque sin querer
me enrede más de lo esperado, y me enfoque más en cumplir con la instalación de Laravel en mi equipo y cumplir con el
login. Sin embargo, aquí dejo las siguientes.

<img width="921" height="526" alt="image" src="https://github.com/user-attachments/assets/6f8241a8-c47c-473a-a39b-59a4df52f5f1" />

<img width="1461" height="574" alt="Captura de pantalla 2026-04-08 105746" src="https://github.com/user-attachments/assets/4dc9448b-a314-4641-92df-8afa84c50485" />

<img width="1427" height="228" alt="Captura de pantalla 2026-04-08 110745" src="https://github.com/user-attachments/assets/141c725f-fa2c-4aae-a1d9-b22dfa6dfded" />

En cuanto a la aplicación en si, esta compuesta por distintos componentes:

<img width="227" height="372" alt="image" src="https://github.com/user-attachments/assets/49d84ce6-9153-4e2d-ac9f-156ed1db267e" />

1. Http/Controllers/Controller.php: Es el controlador base del que heredan todos los demás controladores.
   
2. Http/Controllers/HomeController.php: Es el controlador específico que maneja la lógica de una ruta.

3. Models/User.php: Representa la tabla users en la base de datos.

4. Providers/AppServiceProvider.php: Configura servicios globales de la aplicación

<img width="184" height="96" alt="image" src="https://github.com/user-attachments/assets/93d9299f-c496-4e6d-b7e8-4a853bd052c5" />

5. routes/console.php: Define comandos personalizados de Artisan, la terminal de Laravel

6. routes/web.php: Define las rutas web (enlaces) de la aplicación

Resultado después de instalar Laravel, sus componentes, y hacer el login:

<img width="1916" height="950" alt="Captura de pantalla 2026-04-14 152211" src="https://github.com/user-attachments/assets/6cb4fbf4-07a0-4775-8f9f-ed3e429decc5" />

<img width="1914" height="955" alt="Captura de pantalla 2026-04-14 152226" src="https://github.com/user-attachments/assets/8a7a9347-bba1-4f93-95b3-035e2832062d" />

<img width="1919" height="661" alt="image" src="https://github.com/user-attachments/assets/14e996d4-c8a5-448f-b508-4bf53100b1f4" />

<img width="1906" height="551" alt="image" src="https://github.com/user-attachments/assets/0e7daaa5-44f3-4f61-a0ef-d45ef5491f0e" />

Dificultades y soluciones:

<img width="1917" height="1027" alt="Captura de pantalla 2026-04-08 114825" src="https://github.com/user-attachments/assets/a77e5969-fe3f-4d9e-b200-1b5780bbaf62" />

En la primera mitad de mi intento, estaba usando PowerShell, el cuál me daba problemas aunque ya hubiera instalado los componentes. Luego me recomendaron pasar a
la terminal "normal", y con eso ya pude terminar el proceso.

<img width="1472" height="880" alt="Captura de pantalla 2026-04-14 145554" src="https://github.com/user-attachments/assets/43240125-0637-4ab0-aa61-56880423d760" />

Otro problema fue el susto de que no me funcionaba el servidor. La solución fue simple. En vez de ingresar directo desde el navegador, me fui a la terminal y escribí
el siguiente comando:

<img width="852" height="81" alt="Captura de pantalla 2026-04-14 145821" src="https://github.com/user-attachments/assets/c6c10c7f-0863-4c9e-b969-8406c6c484e9" />

Y con eso, me funcionó normal.

Referencias: 
1. https://laravel.com/docs/13.x
   
2. https://www.w3schools.in/laravel

3. https://es.scribd.com/document/838508468/Manual-de-Laravel


Este laboratorio ha sido desarrollado por el estudiante de la Universidad Tecnológica de Panamá:

Nombre: Joseph Guerra

Correo: joseph.guerra1@utp.ac.pa

Curso: Desarrollo de Software VII

Instructor del Laboratorio: Ing. Irina Fong

Fecha en que se realizó: 8 de abril, 2026











