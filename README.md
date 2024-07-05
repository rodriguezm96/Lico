# Lico
Sistema de ventas para un concesionario
La idea de este proyecto realizado con java fx, es que sirva para la gestion y venta de autos de los concesionario de manera virtual como una especie de catalogo

UNIVERSIDAD DE CORDOBA SEDE LORICA
PROGRAMACION II
PRESENTADO POR:
ANGEL DAVID RODRIGUEZ MEJIA
DOCENTE:
Ruben Baena

CARRERA:
Ingenieria de Sistemas

AÑO:
2024 - Sem 3

Contenido
Sistema de ventas de Licorería ................................................................................................. 1  
Link de repositorio ..................................................................................................................... 2  
Link del prototipo: ▶ Page 1 - Untitled (figma.com) ................................................................ 3  
Introducción............................................................................................................................... 4  
Vistas......................................................................................................................................... 5  

Vista de login.................................................................................................................. 6  
Vista de registro ............................................................................................................. 7  
(.............................................................................................................................................. 8  
Vista principal................................................................................................................. 9  
A. Inicio....................................................................................................................... 9.1  
B. Carrito .................................................................................................................... 9.2  
C. Lista de deseos ....................................................................................................... 9.3  
D. Compras................................................................................................................. 9.4  
E. Salir ............................................................................................................................ 9.5  
UML ................................................................................................................................... 10  

### Introducción  
El sistema de control de ventas se diseñará con el fin de poder ver el catálogo de todos los licores que estén disponibles en el stock de una licorería X. Estos licores tendrán una imagen, la marca, el tipo, la cantidad y el precio. Esto se hará con el fin de que los clientes puedan ver la gama de licores y precios que se ajusten a su poder adquisitivo. El sistema tendrá un login y una opción de registro para los clientes, así podrán comprar los licores. Dentro del sistema, habrá un administrador que se encargará de actualizar la cantidad de licores en stock, además de agregar nuevos productos. Una vez explicado de qué se tratará el sistema, procedemos a explicar cada una de las vistas del prototipo:

### Vistas:

1. **Vista de login:**  
   Esta vista contará con 3 botones: uno para ingresar (🔓), otro para salir (🔙) y el último que mostrará un menú desplegable (☰) para que los clientes puedan registrarse y así entrar al sistema, además de dos cajas de texto, una para el usuario y otra para la contraseña. ![image](https://github.com/rodriguezm96/Lico/assets/173096819/da50519d-2a15-4ed1-a3b2-1e80617d58e7)


2. **Vista de registro:**  
   En esta vista habrá 6 cajas de texto para: identificación, nombre, dirección, teléfono, usuario y contraseña. También tendrá dos botones: uno para volver al login (↩️) y otro para registrar al usuario (✔️). (Nota: Apenas se registre el usuario, se redireccionará a la ventana de inicio) ![image](registro.jpg)

3. **Vista principal:**  
   En la vista principal nos vamos a encontrar con un menú lateral izquierdo donde la opción por defecto mostrará el catálogo de licores disponibles. Habrá 5 opciones:

   ![image](principal.jpg)

   A. **Inicio:**  
      Catálogo de los licores disponibles en el sistema. El usuario podrá darle click a un licor que le interese para ver la información del mismo y elegir la cantidad a comprar o agregarlo a la lista de deseos. Dentro de esta vista también se contará con otras sub-opciones:  
      - Agregar a la lista de deseos.

   B. **Carrito:**  
      Aquí el usuario podrá ver los licores que ha decidido comprar, modificar la cantidad, y proceder al pago.

   C. **Lista de deseos:**  
      En esta sección, el usuario podrá ver los licores que ha agregado a su lista de deseos y moverlos al carrito de compras si así lo desea.

   D. **Compras:**  
      Esta vista mostrará el historial de compras realizadas por el usuario, incluyendo detalles como la fecha de compra, los licores adquiridos y el monto total.

   E. **Salir:**  
      Opción para cerrar sesión y salir del sistema.
