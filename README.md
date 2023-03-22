# ChatGP3

A simple interface for Windows that uses OpenAI's GPT-3 API to generate responses.

![Conversation between User and Assistant](preview.jpg)

##Installation on Windows
1. Install Python and check "Add Python to PATH."
2. Install git.
3. Clone the repository:
```bash
git clone https://github.com/777gt/ChatGP3.git
```
4. Install the required Python package for OpenAI and ttkbootstrap. If you already have them, skip this. Otherwise:
```bash
pip install -r requirements.txt
```
5. After installing everything, you can enter the folder to run the script:
```bash
cd ChatGP3
ChatGP3.pyw
```

## Getting Started

To use this program, you will need an OpenAI API key. You can set your API key by clicking the "Set API Path" button in the top menu of the program. Otherwise, the script will look for a file named "openai_key.txt" in the same directory as the script.

## Usage

To start a conversation with the chatbot, simply type your message into the input box and hit "Enter" or click the "Send" button. The chatbot will respond with a generated message. You can regenerate the chatbot's response by clicking the "♻️" button.

You can save and load conversation histories by clicking the "Save" and "Load" buttons in the top menu. You can also clear the conversation history by clicking the "Clear" button.

## Contributing

If you have any suggestions or find any bugs, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

I am new to coding. I started this year so I expect many errors that will help me learn python further.
