

# Finbot - A Fintech Chatbot

## Description

Finbot is a chatbot designed to provide tailored financial advice and services to users based on their needs. Utilizing natural language processing (NLP) and machine learning (ML) techniques, Finbot understands user intents and delivers personalized responses.

### Key Features

- **Natural Language Processing:** Understands user queries using advanced NLP techniques.
- **Machine Learning:** Employs ML models to provide accurate and personalized financial advice.
- **User Interaction:** Continuously interacts with users to address their financial inquiries.

### Project Structure

- **train_chatbot.py:** 
  - Reads a set of pre-defined intents from a JSON file.
  - Preprocesses text data.
  - Trains a neural network model using TensorFlow.
  - Saves the trained model to a file.
  
- **chatbot.py:**
  - Loads the trained model.
  - Runs a loop to continuously prompt the user for input.
  - Generates responses using the trained model.

## Installation and Usage

### Prerequisites

- Python 3.7+
- TensorFlow
- NumPy
- NLTK

### Setup

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/VIKKIII2269/Finbot.git
    cd Finbot
    ```

2. **Create and Activate a Virtual Environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

### Training the Model

Run the following command to train the model:
```sh
python train_chatbot.py
```

### Running the Chatbot

After training the model, start interacting with the chatbot using:
```sh
python chatbot.py
```

## Contributing

Contributions are welcome! If you encounter any bugs or have ideas for new features, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

