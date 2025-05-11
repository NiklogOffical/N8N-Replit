# n8n on Replit

This is a deployment of n8n workflow automation tool on Replit.

## Setup

This project is configured to run n8n on Replit with the following features:
- Basic authentication enabled
- Automatic port configuration
- Tunneling enabled for webhook access

## Environment Variables

The following environment variables should be set in Replit:
- `N8N_BASIC_AUTH_ACTIVE`: Set to `true` to enable basic authentication
- `N8N_BASIC_AUTH_USER`: Your chosen username
- `N8N_BASIC_AUTH_PASSWORD`: Your chosen password

## Usage

Just click Run in Replit to start your n8n instance. The application will be available at your Replit URL. 