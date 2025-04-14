
# azure_ML

# Azure ML Project

This project demonstrates the use of Azure Machine Learning to process and analyze data using machine learning models. It includes prompts for generating insights and explanations about machine learning concepts.

## Features

- Provides prompts for understanding machine learning concepts.
- Demonstrates the integration of Azure Machine Learning services.
- Offers examples of practical applications of machine learning.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.8 or higher
- Azure CLI
- Azure Machine Learning SDK for Python
- Required Python dependencies (listed in `requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/azure_ML.git
   cd azure_ML
   ```

2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Azure Machine Learning workspace:
   - Log in to Azure using the Azure CLI:
     ```bash
     az login
     ```
   - Create or configure your Azure ML workspace.

## Usage

1. Prepare the input prompts:
   - Edit the file `inputs/prompts.txt` to include the prompts you want to process.

2. Run the application:
   ```bash
   python main.py
   ```

3. View the results:
   - The application will process the prompts and generate outputs based on the machine learning models.

## Environment Variables

The application requires a `.env` file to store sensitive information and configuration details. Below is an example of the required variables:

```plaintext
AIPROJECT_CONNECTION_STRING=<your-azure-ml-connection-string>
AISEARCH_INDEX_NAME=<your-search-index-name>
EMBEDDINGS_MODEL=<your-embeddings-model>
INTENT_MAPPING_MODEL=<your-intent-mapping-model>
CHAT_MODEL=<your-chat-model>
EVALUATION_MODEL=<your-evaluation-model>
```

Replace the placeholders with your actual Azure ML connection string, model names, and other required configurations.

## Code Explanation

- **`inputs/prompts.txt`**: Contains the prompts used for generating insights and explanations.
- **`main.py`**: The main script that processes the prompts and interacts with Azure Machine Learning services.
- **`requirements.txt`**: Lists the Python dependencies required for the project.

## Functionality

The application reads prompts from the `inputs/prompts.txt` file, processes them using machine learning models hosted on Azure, and outputs the results. It is designed to help users understand machine learning concepts and explore practical applications.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.