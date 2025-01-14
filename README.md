![photorealistic-scene-with-warehouse-logistics-operations_23-2151468807](https://github.com/user-attachments/assets/877740d7-2405-4534-8c16-8346fcc97b41)

# Real-Time Notifications

This project demonstrates a real-time notification system using Spring Boot, WebSockets, and STOMP. It includes both server-side and client-side implementations for sending and receiving notifications.

## Features

- Real-time notifications using WebSockets
- Separate notification channels for general messages and order updates
- User-friendly UI for both admin and user views
- Bootstrap for responsive design

## Technologies Used

- Java
- Spring Boot
- WebSockets
- STOMP
- Maven
- HTML/CSS/JavaScript
- Bootstrap

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- A modern web browser

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/mgunawardhana/Real-Time-Notification-Service-Test.git
    cd realtime-notification
    ```

2. Build the project:
    ```sh
    mvn clean install
    ```

3. Run the application:
    ```sh
    mvn spring-boot:run
    ```

### Accessing the Application

- Open your web browser and navigate to `http://localhost:8080/index.html` for the main notification page.
- For admin order updates, navigate to `http://localhost:8080/order.html`.
- For user order tracking, navigate to `http://localhost:8080/order-user-client.html`.

## Project Structure

- `src/main/java/com/example/config/WebSocketConfig.java`: WebSocket configuration.
- `src/main/java/com/example/controller/NotificationController.java`: Controller for general notifications.
- `src/main/java/com/example/controller/OrderNotificationController.java`: Controller for order updates.
- `src/main/java/com/example/controller/OrderUpdate.java`: Model for order updates.
- `src/main/resources/static/index.html`: Main notification page.
- `src/main/resources/static/order.html`: Admin order update page.
- `src/main/resources/static/order-user-client.html`: User order tracking page.
- `src/main/resources/application.properties`: Application properties.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- [Spring Boot](https://spring.io/projects/spring-boot)
- [SockJS](https://github.com/sockjs/sockjs-client)
- [STOMP.js](https://github.com/stomp-js/stompjs)
- [Bootstrap](https://getbootstrap.com/)
