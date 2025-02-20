<h1 align="center" id="title">ELK Stack, Prometheus and Grafana with Docker Compose</h1>

<p align="center">
  <img src="https://socialify.git.ci/suman2280/Monitoring-and-Logging-Stack-with-Docker-Compose/image?custom_description=Simple+Monitoring+and+Logging+Stack+deployed+with+Docker+Compose&description=1&font=Rokkitt&language=1&name=1&owner=1&pattern=Solid&theme=Dark" alt="Monitoring-and-Logging-Stack-with-Docker-Compose" width="640" height="320" />
</p>

<h2>🧑🏻‍💻 Installation Steps</h2>

Follow these steps to set up your environment:

1. **Install Docker and Docker Compose** From Official Documentation. 

2. **Clone This repo**
   ```bash
   git clone https://github.com/suman2280/Monitoring-and-Logging-Stack-with-Docker-Compose.git
   ```
3. **Deploy with Docker Compose**:
   ```bash
   Docker compose up -d
   ```
4. **To Access Elasticsearch**
   ```bash
   <your-public-ip>:9200
   ```
5. **To Access Logstash**
   ```bash
   <your-public-ip>:5044
   ```
6. **To Access Kibana**
   ```bash
   <your-public-ip>:5601
   ```
7. **To Access Prometheus**
   ```bash
   <your-public-ip>:9090
   ```
8. **To Access Grafana**: Default Log in **admin:admin**
   ```bash
   <your-public-ip>:3000
   ```