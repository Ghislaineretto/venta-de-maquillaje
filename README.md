# venta-de-maquillaje, Integrantes: Martinez, Ormaza, Retto
Esta pagina cuenta con una amplia gama de productos como bases, correctores, sombras de ojos, lápices labiales, rímel y otros productos de belleza y cuidado de la piel. Los productos se pueden vender a través de tiendas físicas, plataformas en línea o distribuidores directos.
# Modelo Relacional
![image](https://github.com/user-attachments/assets/a7666d81-6377-4229-b975-ce52acc846db)

# Tablas principales
* Tabla Categorías: Guarda las categorías de productos,por ejemplo: bases, sombras, labiales, etc.
* Tabla Clientes: Contiene información básica de los clientes que realizan compras en la tienda.
* Tabla Productos: Contiene los productos de maquillaje, su nombre, descripción, precio, stock disponible y la relación con la categoría a la que pertenece.
* Tabla Empleados: Esta tabla almacena información sobre los empleados y los pedidos que estan a su nombre.
* Tabla Pedidos: Guarda los pedidos realizados por los clientes, incluyendo el cliente que lo hizo y el empleado que gestionó el pedido. También contiene el total del pedido.
* Tabla DetallePedido: Guarda los productos que fueron comprados en cada pedido, incluyendo la cantidad y el precio unitario al momento de la compra.
