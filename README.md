# AI Agent Llama3 LLaVA IG Post Bot

This Jupyter Notebook demonstrates the implementation of an AI agent using **Llama3** and **LLaVA** for generating Instagram posts. The notebook is designed to be run on Google Colab and includes the necessary steps to set up and use the agent.

## Getting Started

### Prerequisites

To run this notebook, you will need the following:
- Google Colab account
- Python environment with the following packages installed:
  - `colab-xterm`

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    cd Machine-Learning-01
    ```

2. Open the notebook in Google Colab by clicking the link below:  
**Open in Colab**

3. Follow the instructions in the notebook to install necessary dependencies and run the code.

### Running the Notebook

1. Install the `colab-xterm` extension:

    ```python
    !pip install -qq colab-xterm
    %load_ext colabxterm
    %xterm
    ```

2. Open a terminal in Colab and run the following commands to set up the environment:

    ```bash
    curl -fsSL https://ollama.com/install.sh | sh
    ollama serve &
    ollama pull llama3
    ollama pull nomic-embed-text
    ```

### Notebook Contents

- **Markdown cells:** Include descriptions and instructions for using the notebook.
- **Code cells:** Contain Python code to set up and run the AI agent.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
