## YouTube Transcription and Summarization

This repository contains a Python script for transcribing YouTube videos and generating summaries using artificial intelligence. It utilizes the `yt_dlp` library for downloading the videos, the `whisper` library for transcription, and the `langchain` library for summarization.

### Features
- Downloads YouTube videos in MP4 format using `yt_dlp`
- Transcribes the downloaded videos using the `whisper` transcription model
- Generates summaries of the transcribed text using AI-powered summarization models from `langchain`
- Supports prompt-based interactions for summarization and question-answering tasks
- Uses the DeepLake dataset for document storage and retrieval
- Utilizes the OpenAI language model for embeddings and language processing

### Setup and Dependencies
The script requires the following dependencies, which can be installed using pip:
- `langchain==0.0.208`: Language model library for summarization and question-answering
- `deeplake`: Dataset and document storage library
- `openai`: Provides access to the OpenAI language model
- `python-dotenv`: For managing environment variables
- `yt_dlp`: Library for downloading YouTube videos

### Usage
1. Install the required packages by running `pip install -r requirements.txt`.
2. Set up your OpenAI API key and ActiveLoop token by creating a `.env` file with the following format:
3. Modify the `urls` variable in the script to specify the YouTube video URLs you want to transcribe and summarize.
4. Run the script using `python youtube_transcriber.py`.
5. The script will download the videos, transcribe them, and generate summaries based on the transcriptions.

### Contributing
Contributions to the project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

### License
This project is licensed under the [MIT License](LICENSE).

### Disclaimer
Please note that the AI models used in this project are provided by OpenAI and may have limitations or biases. Use the generated summaries and transcriptions with discretion and review the results for accuracy and appropriateness.

### Acknowledgments
The script makes use of the following libraries and frameworks:
- [yt_dlp](https://github.com/yt-dlp/yt-dlp) - A command-line program to download videos from YouTube and other sites
- [whisper](https://github.com/openai/whisper) - An automatic speech recognition system from OpenAI
- [langchain](https://python.langchain.com/) - A Python library for language models and AI-powered tasks
- [DeepLake](https://deeplake.ai/) - A dataset and document storage platform by ActiveLoop

### References
- [yt_dlp Documentation](https://github.com/yt-dlp/yt-dlp)
- [whisper GitHub Repository](https://github.com/openai/whisper)
- [langchain GitHub Repository](https://github.com/hwchase17/langchain)
- [ActiveLoop DeepLake](https://deeplake.ai/)

Feel free to explore and contribute to this project!
