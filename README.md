# Rest Api Application

This project sets up a Rest API and monitoring the stack using Docker Compose, including Prometheus for metrics collection and Grafana for visualization and dashboarding.

## Prerequisites

- Java 18 or high
- Docker
- Docker Compose 3.3 or higher

## Getting Started

1. Clone the repository: `git clone https://github.com/your-repo/monitoring-stack.git`
2. Navigate to the project directory: `cd monitoring-stack`
3. Start the stack: `docker-compose up -d`

This will run the Rest Api application, pull the necessary Docker images and start the containers in the background.

## Stop the stack

Run `docker-compose down` to stop the stack and remove the containers. The data directory will persist on your machine.

## Access the services:

- Rest Api: http://localhost:8080
- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).
