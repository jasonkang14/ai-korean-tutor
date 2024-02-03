# Korean AI Tutor Project

## Project Description
This project aims to create an innovative Korean AI tutor by integrating advanced AI technologies. It currently utilizes the OpenAI ChatCompletion API for generating responsive, conversational AI interactions. Additionally, it leverages Naver Clova's Speech-to-Text (STT) and Text-to-Speech (TTS) capabilities, creating a more interactive and engaging learning experience for users looking to improve their Korean language skills.


## Features
- [Chat Completions](https://platform.openai.com/docs/guides/text-generation/chat-completions-api): Creates an interactive chat thread for text-based English tutoring.
- [Clova Speech Recognition](https://api.ncloud-docs.com/docs/en/ai-naver-clovaspeechrecognition): Implements Speech to Text functionality, allowing users to speak and have their speech converted to text.
- [Clova Voice](https://api.ncloud-docs.com/docs/en/ai-naver-clovavoice): Converts the language model's responses into audio, enabling an auditory learning experience.

## Prerequisites
- OpenAI API keys for Chat Completions
- Naver Cloud ID and Secret for Clova Speech Recognition and Clova Voice
- Python 3.6 or later.
- Jupyter Notebook.

## Installation
1. Clone the repository:

```bash
git clone git@github.com:jasonkang14/ai-korean-tutor.git
cd ai-korean-tutor
```

2. Install required Python packages:
```bash
pip install -r requirements.txt
```

3. Setup API keys:

Set your OpenAI API keys as environment variables and store it in `.env` as `OPENAI_API_KEY`. Naver Cloud Client ID and Client Secret as `NCLOUD_CLIENT_ID` and `NCLOUD_CLIENT_SECRET` respectively

## Running the Project

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

you can also use VS Code if you would like

2. Open the project notebook (e.g., ai_korean_tutor.ipynb) in the Jupyter interface.
3. Run the cells in sequence, following any instructions provided within the notebook.

## Usage
- Interact with the chatbot via the Jupyter Notebook interface. 
- Use a microphone for the Speech to Text feature, speaking in Korean. The Clova Speech Recognition API will transcribe your speech.
- Listen to the TTS audio responses from the language model for auditory learning and practice.

## Contributions
- Contributions to this project are welcome! Please refer to the contribution guidelines for more information.

## Future Developments
The project is poised for an important upgrade. We have applied to gain access to Naver Clova Studio, with the goal of integrating Clova's Chat Completion API. This transition from OpenAI's API to Clova's is anticipated to enhance the tutor's capabilities, especially in handling Korean language nuances more effectively. Once access is approved and integrated, the codebase will be updated to reflect these improvements.