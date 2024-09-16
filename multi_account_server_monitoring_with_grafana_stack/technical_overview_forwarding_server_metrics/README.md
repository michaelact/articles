## Highlight

- **// Install node-exporter**: This sets up the **Node-Exporter**, a tool that collects Linux system metrics (like CPU, memory, disk usage) and makes them available for Prometheus to read.
- **// Scrape metrics from above exporter**: Gather the metrics from the Node-Exporter and send them to a central server (remote write).
- **// Send metrics to a Prometheus remote_write endpoint**: This sets up the connection to the remote Prometheus server where the metrics will be stored.

## Deployment

### Prerequisites

Make sure you have the following installed on your system:

- [Rancher Desktop](https://rancherdesktop.io/) or [Docker](https://docs.docker.com/engine/install/)

### Setup

1. **Clone the Repository:**
   ```shell
   git clone https://github.com/michaelact/articles
   cd multi_account_server_monitoring_with_grafana_stack/technical_overview_forwarding_server_metrics/
   ```

2. **Start the Application:**
   ```shell
   docker compose up -d
   ```

2. **View the Logs:**
   ```shell
   docker compose logs -f
   ```
