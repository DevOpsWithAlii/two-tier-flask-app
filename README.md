 
# Flask App with MySQL Docker Setup

This is a simple Flask app that interacts with a MySQL database. The app allows users to submit messages, which are then stored in the database and displayed on the frontend.

## Prerequisites

Before you begin, make sure you have the following installed:

- Docker
- Git (optional, for cloning the repository)

## Setup

1. Clone this repository (if you haven't already):

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo-name
   ```

3. Create a `.env` file in the project directory to store your MySQL environment variables:

   ```bash
   touch .env
   ```

4. Open the `.env` file and add your MySQL configuration:

   ```
   MYSQL_HOST=mysql
   MYSQL_USER=your_username
   MYSQL_PASSWORD=your_password
   MYSQL_DB=your_database
   ```

## 📊 Monitoring & Observability (Grafana + Prometheus)

The project includes a complete monitoring setup using **Prometheus, Grafana, cAdvisor, Node Exporter, and MySQL Exporter** to visualize application, container, and database metrics.

### 🔹 Docker & Container Monitoring
![Docker Monitoring](https://github.com/DevOpsWithAlii/two-tier-flask-app/blob/main/templates/Screenshot%20(322).png)

### 🔹 cAdvisor – Container Resource Usage
![cAdvisor Dashboard](https://github.com/DevOpsWithAlii/two-tier-flask-app/blob/main/templates/Screenshot%20(326).png)

### 🔹 Application & Database Metrics
![MySQL Metrics](https://github.com/DevOpsWithAlii/two-tier-flask-app/blob/main/templates/Screenshot%20(323).png)




## 📈 What This Dashboard Shows

- Container-level CPU & Memory usage for Flask app, MySQL, Redis, Prometheus, Grafana

- Real-time resource consumption using cAdvisor

- MySQL database performance metrics (connections, memory usage)

- Infrastructure metrics via Node Exporter

- Centralized visualization using Grafana with Prometheus as data source

## Monitoring Stack
- Prometheus – Metrics collection and storage

- Grafana – Visualization and dashboards

- cAdvisor – Docker container metrics

- Node Exporter – VM / EC2 system metrics

- MySQL Exporter – Database-level metrics

```






