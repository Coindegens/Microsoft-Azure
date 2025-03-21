# Azure AI Services 

This repository contains two methods that demonstrate how to use Azure AI services to detect the language of a given text. The projects use both the SDK client and REST client approaches.

## Prerequisites

- Azure subscription
- Visual Studio Code
- Git
- Python 3.x
- Azure AI-Service-Reource

## Projects

### SDK Client

The `sdk-client` project uses the Azure SDK for Python to interact with the Text Analytics service.

#### Usage

1. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

2. Set up your environment variables in a `.env` file:
    ```env
    AI_ENDPOINT=<your_endpoint>
    AI_KEY=<your_key>
    ```

3. Run the script:
    ```sh
    python sdk-client.py
    ```

### REST Client

The `rest-client` project uses direct HTTP requests to interact with the Text Analytics service.

#### Usage

1. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

2. Set up your environment variables in a `.env` file:
    ```env
    AI_ENDPOINT=<your_endpoint>
    AI_KEY=<your_key>
    ```

3. Run the script:
    ```sh

## Note

Ensure that you replace `<your_endpoint>` and `<your_key>` with your actual Azure AI service endpoint and key. Do not share your endpoint and key publicly.# Microsoft-Azure

## Contributing

This repository is for learning purposes as part of Microsoft Learn modules. Please refer to Microsoft Learn for more information about contributing.
    python rest-client.py
    ```

