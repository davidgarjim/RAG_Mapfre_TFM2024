# RAG ChatBot


## Prerequisites

Before you can start using the RAG Bot, make sure you have the following prerequisites installed on your system:

- Python 3.12 or higher



## Installation

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/ssillerom/tfm_valley_2025_g3.git
    cd RAG_CHATBOT
    ```

2. Install dependencies 
    ```bash
    poetry install
    ```

3. Access the enviroment:
    ```bash
    poetry env activate
    ```

4. Configure the GOOGLE API KEY
    - Create a google_api_key.txt file
    - Paste your API key into the file.


5. Run
    ```bash
    chainlit run app.py -w
    ```
