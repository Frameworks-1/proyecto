# proyecto
lumina
![WhatsApp Image 2026-01-20 at 9 02 09 PM](https://github.com/user-attachments/assets/d673bfea-411d-4c0f-8d4f-dcc8d643d8bd)

Descripcion 

En ocasiones, los clientes que consumen productos Natura no conocen todo el catálogo disponible, sus beneficios o no saben dónde adquirirlos fácilmente.
La Tienda Natura permite a los usuarios realizar sus compras en línea de manera sencilla, ofreciendo una experiencia intuitiva para encontrar productos de belleza, cuidado personal y bienestar mediante una barra de búsqueda, visualizar información detallada y adquirirlos hasta agotar existencias.

Requerimientos funcionales

Visualizar la lista de productos Natura disponibles.
Registrar productos seleccionados en el carrito de compras.
Filtrar productos mediante un campo de búsqueda.
Visualizar la información básica de cada producto (nombre, precio y descripción).
Visualizar recomendaciones de productos relacionados con el producto seleccionado (por ejemplo, productos de la misma línea o categoría).

requerimientos no funcionales

1. Adaptabilidad
La tienda cuenta con un diseño responsive, garantizando una correcta visualización y usabilidad en dispositivos móviles, tabletas y computadoras de escritorio mediante el uso de CSS.
2. Persistencia
La aplicación deberá conservar los productos agregados al carrito de compras mediante el uso de LocalStorage, incluso si el usuario recarga o cierra el navegador.

3. Accesibilidad
4. La interfaz deberá cumplir con criterios básicos de accesibilidad, utilizando etiquetas HTML semánticas y roles ARIA, permitiendo su uso con lectores de pantalla y facilitando la navegación para todos los usuarios.

   Tecnologías y Herramientas del Ecosistema

Framework Frontend: React
Manejo de Estado Global:
Context API, ya que permite compartir el estado del carrito de compras entre componentes sin necesidad de pasar props manualmente, manteniendo el código organizado y escalable.
Consumo de Datos:
Fetch API, utilizada para obtener los datos de los productos desde un archivo JSON local o una API simulada.
Estilizado:
CSS tradicional / CSS Modules, para mantener un diseño limpio, responsivo y fácil de mantener.
Despliegue:
Netlify, por su facilidad de integración con GitHub y despliegue automático del proyecto.


<img width="3826" height="2625" alt="Untitled diagram-2026-01-22-032652" src="https://github.com/user-attachments/assets/ca996067-a800-4bfd-a4ca-aacc982e9237" />

