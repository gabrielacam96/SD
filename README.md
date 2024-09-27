# SD
Sistemas Distribubidos

---

# EasyCab - Sistemas Distribuidos

## Descripción

*EasyCab* es un sistema distribuido que simula la gestión de una flota de taxis autónomos en tiempo real. Los taxis reciben instrucciones de una central (EC_Central) para recoger clientes y transportarlos a sus destinos en una ciudad representada por una matriz de 20x20.

## Componentes

- **EC_Central**: Central de control que gestiona los taxis y las solicitudes de clientes.
- **EC_DE**: Control de cada taxi que sigue las instrucciones de la central.
- **EC_S**: Sensores del taxi que reportan anomalías en el trayecto.
- **EC_Customer**: Aplicación para que los clientes soliciten un taxi.

## Tecnologías

- **Sockets** para la comunicación entre los módulos.
- **Kafka** para el streaming de eventos.
- **Python/Java** para la implementación del sistema.
- **Docker** para el despliegue distribuido.

## Funcionamiento

Los clientes solicitan taxis a través de la central, que asigna taxis disponibles y gestiona sus movimientos y contingencias durante el servicio.
