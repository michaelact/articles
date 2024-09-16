## Highlight

- **// Scrape metrics from the exporter**: Updates the `forward_to` variable to send metrics to relabel rules.
- **// Get AWS account ID**: Retrieves the EC2 instance identity using HTTP.
- **// Add AWS metadata to metrics**: Adds new labels to metrics using relabeling rules.

## Deployment

### Prerequisites

Make sure you have the following installed on your system:

- [Rancher Desktop](https://rancherdesktop.io/) or [Docker](https://docs.docker.com/engine/install/)

### Setup

1. **Clone the Repository:**
   ```shell
   git clone https://github.com/michaelact/articles
   cd multi_account_server_monitoring_with_grafana_stack/labels_by_cloud_provider_account_and_region/
   ```

2. **Start the Application:**
   ```shell
   docker compose up -d
   ```

2. **View the Logs:**
   ```shell
   docker compose logs -f
   ```
