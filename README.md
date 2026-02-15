SpeedFast – Sistema de Gestión de Entregas

Proyecto desarrollado para la asignatura Desarrollo Orientado a Objetos II.

Esta aplicación de escritorio fue implementada en Java utilizando Swing, aplicando principios de programación orientada a objetos y organización en capas (modelo, controlador y vista).

Descripción del Proyecto

SpeedFast es un sistema básico de gestión de pedidos que permite:

Registrar nuevos pedidos.

Visualizar pedidos existentes en una tabla.

Asignar repartidores a pedidos.

Gestionar la información en memoria sin conexión a base de datos.

El objetivo principal es demostrar la correcta implementación de interfaces gráficas en Java y la integración con una estructura orientada a objetos.

Estructura del Proyecto

El proyecto está organizado en los siguientes paquetes:

src
 ├── main
 │    └── Main.java
 │
 ├── model
 │    └── Pedido.java
 │
 ├── controller
 │    └── PedidoController.java
 │
 └── view
      ├── VentanaPrincipal.java
      ├── VentanaRegistroPedido.java
      ├── VentanaListaPedidos.java
      └── VentanaAsignarRepartidor.java

      Cómo ejecutar el proyecto

Clonar el repositorio o descargar el archivo comprimido.

Abrir la carpeta del proyecto en IntelliJ.

Verificar que el SDK esté configurado.

Ejecutar la clase:

main.Main
