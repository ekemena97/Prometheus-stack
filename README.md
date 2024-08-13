# Prometheus Stack

This project sets up a monitoring and alerting stack using Prometheus, Grafana, and Alertmanager. The stack is designed to collect metrics and logs from Prometheus, visualize them in Grafana, and send alerts via email through Alertmanager.

## Components

1. **Prometheus**: A monitoring system that collects metrics and logs from various sources.
2. **Grafana**: A visualization tool that displays data collected by Prometheus.
3. **Alertmanager**: A component that handles alerts sent by Prometheus, including routing, grouping, and sending them via email.

## Prerequisites

- Docker and Docker Compose installed on your machine.
- Access to an SMTP server for sending email alerts.
- A GitHub repository to store your project files.

## Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
