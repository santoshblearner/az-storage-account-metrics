# Azure Storage Account Metrics Workbook Template

This repository contains an Azure workbook template for analyzing and monitoring Azure Storage Accounts. The workbook provides insights into metrics, capacity, and performance of storage accounts across different subscriptions and resource groups.

## Features

- **Subscription-based Filtering**: Analyze storage accounts across multiple subscriptions.
- **Resource Group-based Filtering**: Drill down into specific resource groups.
- **Metrics**: Provides detailed metrics on transactions, latency, and storage capacity across Azure Storage services (Blob, File, Queue, and Table).
- **Custom Time Range**: Allows selection of various time ranges to view data trends.
- **Capacity Insights**: Visualize the used capacity across different storage services (Blob, File, Queue, Table).
- **Export to Excel**: Easily export the displayed data for further analysis.

## Workbook Structure

The workbook is designed with multiple sections:
- **Subscription & Resource Group Selection**: Users can filter data based on subscriptions and resource groups.
- **Metrics**: Shows transaction counts, end-to-end latency, and server latency metrics for selected storage accounts.
- **Capacity**: Displays used capacity and capacity trends for Blob, File, Queue, and Table services.
- **KQL Queries**: Integrated with KQL (Kusto Query Language) for querying storage account metadata and properties.

## How to Use

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/santoshblearner/az-storage-account-metrics.git
    ```
2. Deploy this ARM template by using either the [Azure portal](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-portal#deploy-resources-from-custom-template), [the command-line interface](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-cli), or [PowerShell](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-powershell).
3. Customize the workbook as needed by selecting the desired subscriptions, resource groups, and storage accounts.

## Requirements

- **Azure Monitor**: Ensure that Azure Monitor is enabled in your Azure subscription.
- **Azure Storage Account**: This workbook template is designed to monitor Azure Storage Accounts only.
- **Kusto Query Language (KQL)**: Some sections use KQL queries to retrieve data.

## Contribution

Contributions are welcome! If you encounter issues or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
