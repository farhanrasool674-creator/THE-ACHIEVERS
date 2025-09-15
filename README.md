# Echo Verse - AI-Powered Multilingual Audiobook Creator

[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://python.org/)
[![Gradio](https://img.shields.io/badge/Gradio-4.0+-green)](https://gradio.app/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Deploy](https://img.shields.io/badge/Deploy-Hugging%20Face-orange)](https://huggingface.co/spaces)

Transform text, PDFs, and audio into professional audiobooks in 25+ languages using cutting-edge AI models.

## Features

- **Multi-Source Input**: Process text, PDF documents, and audio files
- **25+ Languages**: Support for major world languages
- **AI Enhancement**: Google Gemini AI text improvement
- **Speech Recognition**: IBM Granite model for audio transcription
- **Professional TTS**: High-quality Google Text-to-Speech
- **User Customization**: Category-based text enhancement
- **Modern UI**: Clean, accessible dark interface

## Supported Languages

English, Hindi, Urdu, Telugu, Tamil, Bengali, Gujarati, Kannada, Malayalam, Marathi, Punjabi, Odia, Assamese, Spanish, French, German, Italian, Portuguese, Russian, Japanese, Korean, Chinese, Arabic, Turkish, Thai, Vietnamese

## Quick Start

### Local Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/echo-verse.git
cd echo-verse
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Get API Key**
- Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
- Create a free Gemini API key

4. **Run the application**
```bash
python app.py
```

5. **Open your browser** and go to the displayed URL

### Cloud Deployment

#### Hugging Face Spaces (Recommended)
1. Fork this repository
2. Create a new Space on [Hugging Face](https://huggingface.co/spaces)
3. Connect your forked repository
4. The app will deploy automatically

#### Other Platforms
- **Railway**: Connect GitHub repo, set start command to `python app.py`
- **Render**: Similar setup with `python app.py`
- **Google Colab**: Upload files and run `python app.py`

## Usage

1. **Configure API**: Enter your Gemini API key
2. **Choose Input**: Provide text, upload PDF, or record/upload audio
3. **Select Options**: 
   - Target language for translation
   - User category (student, professional, visually impaired, other)
   - Enable AI enhancement and slow speech as needed
4. **Process**: Click "Create Audiobook" to generate results
5. **Download**: Get your processed text and audio files

## Technical Details

### Requirements
- Python 3.8+
- CUDA-compatible GPU (recommended for Granite model)
- Internet connection for API calls

### Key Components
- **Frontend**: Gradio web interface
- **Text Enhancement**: Google Gemini Pro
- **Speech-to-Text**: IBM Granite 3.3 2B model
- **Text-to-Speech**: Google gTTS
- **Translation**: Google Gemini Pro
- **PDF Processing**: PyPDF2

### Performance
- CPU: Basic functionality works
- GPU: Recommended for Granite STT model
- RAM: 4GB minimum, 8GB+ recommended
- Storage: Models downloaded automatically (~5GB)

## API Keys

The app requires a Google Gemini API key for:
- Text enhancement
- Language translation
- Content optimization

Get your free key at: https://makersuite.google.com/app/apikey

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Gemini AI for text processing
- IBM Granite team for speech models
- Hugging Face for model hosting
- Gradio team for the web framework

## Support

- Create an issue for bug reports
- Check existing issues before creating new ones
- Provide detailed information for faster resolution

## Changelog

### v1.0.0
- Initial release
- Multi-language support
- PDF and audio processing
- Gemini AI integration
- IBM Granite STT
- Modern web interface

---

Built with ❤️ using Python, Gradio, and cutting-edge AI models.
