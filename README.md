# HealthMate-A-Med-ChatBot

This Medical Bot is a powerful tool designed to provide medical information by answering user queries using state-of-the-art language models and vector stores. 


## Installation and Running 

1. Clone this repository to your local machine.

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. 

5. Set up the necessary paths and configurations, including the `DB_FAISS_PATH` variable and other configurations.

6. Run the Chatbot:
    ```bash
   chainlit run model.py -w
    ```


## Usage

The Langchain Medical Bot can be used for answering medical-related queries. To use the bot, you can follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a medical-related query to the bot.

3. The bot will provide a response based on the information available in its database.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.

