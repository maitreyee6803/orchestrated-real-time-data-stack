# orchestrated-real-time-data-stack
A containerized infrastructure designed for seamless data ingestion, storage, and visualization. This project demonstartes integration of multiple open-source tools into a unified, deployable environment.

# System Integration
Stack uses **Docker-compose** to orchestrate three core components:
Node-red : for logic based data processing and routing
InfluxDB : High-performance time-series databases fro persistent storage
Grafana : Advanced visualization platform for real-time monitoring.
# technical implementation
Orchestration: managed multi-container deployment to enusre environment parity
Networking : established a dedicated virtual bridge network for secure inter-service communication
Persistence : configured docker volume for persistent data storage across container lifecycles
