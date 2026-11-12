<img width="2048" height="2048" alt="diagrama de casos de uso" src="https://github.com/user-attachments/assets/1205ee54-e161-49aa-9ff8-bee6d188bc51" />

Diagrama de Casos de Uso de "Sabores de Babilonia".

El siguiente diagrama de casos de uso representa la interacción entre los actores principales del sistema web Sabores de Babilonia y las funcionalidades disponibles dentro de la plataforma de comercialización de frutos deshidratados. El objetivo de este modelo es identificar las acciones que pueden realizar los usuarios y administradores dentro del sistema, así como la relación existente entre los procesos de compra, gestión de productos y administración del negocio.

Actor: Cliente

El actor Cliente representa a las personas que acceden a la plataforma para consultar y adquirir productos saludables. Las funcionalidades asociadas a este actor son:

Registrarse

Permite al usuario crear una cuenta dentro de la plataforma proporcionando información personal como nombre, correo electrónico, dirección y datos de contacto. Este proceso es necesario para acceder a funcionalidades avanzadas y realizar compras.

Iniciar Sesión

Una vez registrado, el cliente puede autenticarse en el sistema mediante sus credenciales de acceso. Esto permite acceder a información personalizada y al historial de pedidos.

Consultar Productos

El cliente puede explorar el catálogo de productos disponibles, incluyendo frutos deshidratados, infusiones y snacks saludables. Además, puede consultar información relevante como precios, beneficios nutricionales y disponibilidad.

Gestionar Carrito

Esta funcionalidad permite agregar, modificar o eliminar productos seleccionados antes de realizar la compra definitiva.

Realizar Pedido

Una vez confirmados los productos en el carrito, el cliente puede generar una orden de compra indicando la dirección de entrega y los detalles necesarios para el envío.

Pasarela de Pago

Después de crear el pedido, el sistema se conecta con una pasarela de pago para procesar la transacción de forma segura. La validación del pago es necesaria para confirmar la compra y continuar con el procesamiento del pedido.

Actor: Administrador

El actor Administrador es responsable de supervisar y controlar las operaciones internas del negocio.

Gestionar Productos

Permite registrar nuevos productos, modificar información existente, actualizar precios y eliminar productos que ya no se comercialicen.

Gestionar Inventario

Controla las existencias disponibles de cada producto, registrando entradas y salidas de inventario y garantizando la disponibilidad de stock para los clientes.

Gestionar Pedidos

Permite visualizar las órdenes de compra generadas por los clientes, actualizar su estado y realizar el seguimiento desde la preparación hasta la entrega.

Generar Reportes

Utiliza la información almacenada en la base de datos para producir informes relacionados con ventas, pedidos, productos más vendidos, niveles de inventario y desempeño general del negocio.

Flujo General del Sistema

El diagrama muestra el proceso principal que sigue un cliente dentro de la plataforma:

- El cliente se registra en el sistema.
- Posteriormente inicia sesión.
- Consulta los productos disponibles.
- Añade productos al carrito de compras.
- Realiza el pedido.
- El sistema procesa el pago mediante la pasarela de pago.
- Una vez confirmado el pago, el pedido queda registrado.

Paralelamente, el administrador administra el catálogo de productos, controla el inventario, gestiona los pedidos recibidos y genera reportes para apoyar la toma de decisiones estratégicas.

Importancia del Diagrama

Este diagrama de casos de uso permite identificar claramente los requerimientos funcionales del sistema, definir las responsabilidades de cada actor y establecer la interacción entre los usuarios y la plataforma. Además, sirve como base para el diseño de la base de datos SQL, la implementación del sistema web y el desarrollo de los módulos que conforman la solución tecnológica de Sabores de Babilonia.

Conclusión

El diagrama de casos de uso proporciona una visión general del funcionamiento de la plataforma web, mostrando cómo los clientes pueden interactuar con los productos y realizar compras en línea, mientras que los administradores gestionan la información comercial y operativa del negocio. Esta representación facilita la planificación, desarrollo e implementación del sistema, asegurando que los procesos de venta, inventario y atención al cliente funcionen de manera integrada y eficiente.
