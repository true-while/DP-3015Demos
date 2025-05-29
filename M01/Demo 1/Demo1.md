# DEMO 1: Azure Cosmos DB Setup Script

## Overview

This script, written in Azure CLI with PowerShell syntax, automates the provisioning of an Azure Cosmos DB environment. It includes the creation of a resource group, Cosmos DB account, SQL API database, and container. The script is designed for quick setup, making it ideal for development, testing, or demonstration purposes.

## Script Details

### Features:
1. **Resource Group Creation**:
   - Creates a resource group named `DP420-RG` in the `canadacentral` Azure region.

2. **Cosmos DB Account Creation**:
   - Generates a unique name for the Cosmos DB account using a random value to avoid naming collisions.
   - Creates the Cosmos DB account in the specified resource group.

3. **SQL API Database Creation**:
   - Creates a SQL API database named `DP420Demo` in the Cosmos DB account.

4. **Container Creation**:
   - Creates a container named `TheCloudShops` in the `DP420Demo` database.
   - Configures the container with:
     - Partition key path: `/OrderAddress/City`
     - Throughput: `400 RU/s`

### Prerequisites:
- Azure CLI installed and authenticated.
- Sufficient permissions to create resources in the Azure subscription.

### Usage:
1. Open a terminal with Azure CLI installed.
2. Run the script to provision the Cosmos DB environment.

### Notes:
- The `$RANDOM` variable ensures the Cosmos DB account name is unique.
- The partition key path (`/OrderAddress/City`) is predefined for the container.

## File Information

- **Filepath**: `c:\MOC\DP-3015\Slides\M01\Demo 1\cosmos-account.azcli`
- **Purpose**: Automates the setup of an Azure Cosmos DB environment.

## Disclaimer

This script is intended for demonstration and testing purposes. Ensure you review and modify it as needed before using it in a production environment.