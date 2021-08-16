# Generate a Azure Blob Storage SAS Token
That's how you can get a SAS Token for containers using a Blob Storage Connection String.

## Prerequisites
- .NET SDK 5.0
- Azure Blob Storage Connection String

## How to Run

1. Set an environment variable named as ``AZURE_STORAGE_CONNECTION_STRING`` and set it's value with your connection string;
2. Open up your terminal pointed to the project directory;
3. Type ``dotnet restore`` and press *enter* to install Nuget Packages;
4. type ``dotnet run`` and press *enter*;
5. The SAS Token will be printed to your terminal.

