AI YouTube Summarizer is a powerful desktop application that leverages artificial intelligence to provide concise summaries of YouTube videos. Built with Python and powered by the Claude API, this tool offers a user-friendly interface for quick and efficient video content analysis.
Features

**YouTube Video Summarization: **
Enter a YouTube URL and get an AI-generated summary of the video content.
**Multilingual Support**: Translate summaries into English, Russian, or Urdu.
**Detailed Explanations:** Generate in-depth explanations of topics with figures and examples.
**Save Functionality:** Export summaries and explanations to Word documents for easy sharing and reference.
****Dark Mode:**  Toggle between light and dark themes for comfortable viewing in any environment.
**Fullscreen Mode:**  Maximize your workspace with a fullscreen option (press ESC to exit).
**Animated UI:** Enjoy a visually appealing interface with animated title and background elements.
**Requirements**
Python 3.7+
Anthropic API key (for Claude AI integration)
**Dependencies**
anthropic: For interacting with the Claude AI API
youtube_transcript_api: To fetch video transcripts
tkinter: For the graphical user interface
ttkthemes: To apply themed widgets
pillow: For image processing
python-docx: To create and manipulate Word documents
**Installation**
Clone the repository:
Copygit clone https://github.com/yourusername/ai-youtube-summarizer.git
cd ai-youtube-summarizer
Install the required dependencies:
Copypip install -r requirements.txt
Set up your Anthropic API key:
Sign up for an account at Anthropic
Obtain your API key
Replace "your-api-key-here" in the code with your actual API key
**Usage**
Run the application:
Copypython main.py
Enter a YouTube video URL in the input field.
Click the "Summarize" button to generate a summary.
Use additional features like translation, detailed explanation, or saving to Word as needed.
**Contributing**
Contributions are welcome! Please feel free to submit a Pull Request.
**License**
This project is licensed under the MIT License - see the LICENSE file for details.
**Acknowledgments**
Anthropic for the Claude AI API
YouTube Transcript API for transcript fetching capabilities
**Disclaimer**
This tool is for educational and research purposes only. Ensure you comply with YouTube's terms of service when using this application.
