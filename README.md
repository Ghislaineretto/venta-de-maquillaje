# venta-de-maquillaje
Esta pagina cuenta con una amplia gama de productos como bases, correctores, sombras de ojos, lápices labiales, rímel y otros productos de belleza y cuidado de la piel. Los productos se pueden vender a través de tiendas físicas, plataformas en línea o distribuidores directos.
# Modelo Relacional
![image](https://github.com/user-attachments/assets/412172c3-a21b-4fe9-9559-4cf7d86eabe0)
# Tablas principales
Tabla Categorías: Guarda las categorías de productos (por ejemplo, bases, sombras, labiales).
Tabla Clientes: Contiene información básica de los clientes que realizan compras en la tienda.
Tabla Productos: Contiene los productos de maquillaje, su nombre, descripción, precio, stock disponible y la relación con la categoría a la que pertenece.
Tabla Empleados: (opcional) Si deseas gestionar quién maneja los pedidos, esta tabla puede almacenar información sobre los empleados.
Tabla Pedidos: Guarda los pedidos realizados por los clientes, incluyendo el cliente que lo hizo y el empleado que gestionó el pedido. También contiene el total del pedido.
Tabla DetallePedido: Guarda los productos que fueron comprados en cada pedido, incluyendo la cantidad y el precio unitario al momento de la compra.
