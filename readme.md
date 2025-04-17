# Chatbot: Manish Mandal Persona

This project is a simple implementation of a chatbot with a personalized persona of Manish Mandal, a highly focused and technically driven developer passionate about AI, cybersecurity, web development, and DSA.

The chatbot uses OpenAI's GPT-4 API to simulate conversations in English, Hindi, and Nepali.





## ScreenShots


<img width="960" alt="1" src="https://github.com/user-attachments/assets/7254a063-47f6-44af-924f-5aea9af3aed1" />
<img width="960" alt="2" src="https://github.com/user-attachments/assets/a4024109-cfe6-442e-ac7d-e12feea65fd7" />

<img width="960" alt="3" src="https://github.com/user-attachments/assets/cdc200fa-c8b3-4296-b987-a8a85d1ce703" />






## Features

- Chat with a personalized AI persona based on Manish Mandal's profile.
- Supports responses in multiple languages (English, Hindi, and Nepali).
- Can be integrated with OpenAI's GPT-4 API for high-quality conversational abilities.
- Uses environment variables for API key management.

## Technologies Used

- **Python**: Main programming language used for implementing the bot.
- **OpenAI API**: GPT-4 model for generating responses based on the personalized prompt.
- **dotenv**: To load environment variables from a `.env` file for secure handling of the OpenAI API key.
- **OpenAI Python SDK**: Client library for interacting with OpenAI's GPT-4.

## Setup Instructions

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/maneeish/ManishMandalPersonaChatbot.git
    cd ManishMandalPersonaChatbot
    ```

2. Create a virtual environment and activate it.

    For Windows:
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

    For macOS/Linux:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies.

    ```bash
    pip install -r requirements.txt
    ```

4. Set up your OpenAI API key.

    - Create a `.env` file in the root directory of the project.
    - Add your API key to the `.env` file:

    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

5. Run the chatbot.

    ```bash
    python chat.py
    ```

    Start chatting with the Manish Mandal persona. Type 'exit' to end the conversation.

## Project Structure

- **chat.py**: Main script where the chatbot logic is implemented.
- **.env**: Environment file where the OpenAI API key is stored.
- **requirements.txt**: List of Python dependencies required for the project.

## Project Roadmap

- Add more persona-based customization.
- Integrate a web interface for better user interaction.
- Implement advanced conversation topics such as AI, Cybersecurity, and Web Development.

## Links

- [LinkedIn](https://www.linkedin.com/in/manish-mandal-6b7212295/)
- [Twitter](https://x.com/ManishMand92542)
- [GitHub](https://github.com/maneeish)
- [Facebook](https://www.facebook.com/share/1BjfrjyKxK/)
- [Gmail](mailto:maneeish09@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
