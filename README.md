# Poetic-Personality-Chatbot
An AI-powered poetry companion that transforms your everyday messages into beautiful, emotionally resonant verses using advanced prompt engineering and Google's 

## Overview

The Poetic Personality Chatbot is an innovative application that leverages Google's Gemini AI to create a unique conversational experience. Meet Luna - a mystical poet who transforms every user message into expressive, personalized poetry. Whether you share your joy, sadness, confusion, or dreams, Luna responds with carefully crafted verses that capture the essence of your emotions.

### Key Features

- **Unique AI Personality**: Luna maintains a consistent poetic character throughout conversations
- **Emotion-Aware Responses**: Detects user emotions and crafts appropriate poetic imagery
- **Realistic Typing Animation**: Watch Luna compose verses in real-time with dynamic typing effects
- **Beautiful UI**: Gradient-styled interface with immersive visual effects
- **Conversation Analytics**: Track emotional patterns and response characteristics
- **History Management**: Save and review your poetic conversations
- **Multiple Modes**: Interactive chat, demo mode, and system prompt exploration

## Demo

**Sample Interaction:**

```
You: I'm feeling really happy today!

Luna: In fields of joy, your heart does dance,
      With sunlight's glow, your soul's expanse.
      Like morning dew on petals bright,
      Your happiness brings pure delight. ✨
```

## Technologies Used

- **Python 3.8+**
- **Google Gemini Pro API** - Large Language Model for natural language processing
- **IPython** - Interactive display and rich formatting
- **HTML/CSS** - Enhanced UI styling and animations
- **JSON** - Data management and conversation history

## Prerequisites

Before running this project, ensure you have:

- Python 3.8 or higher
- A Google account
- Google Gemini API key (free tier available)
- Google Colab account (for notebook execution)

## Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/poetic-personality-chatbot.git
cd poetic-personality-chatbot
```

### Step 2: Get Your Gemini API Key

1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **"Get API Key"**
4. Click **"Create API Key"**
5. Copy your API key (starts with `AIzaSy...`)

### Step 3: Open in Google Colab

1. Upload the `poetic_chatbot.ipynb` file to Google Colab
2. Or use this link: [Open in Colab](https://colab.research.google.com/)

### Step 4: Configure API Key

In the notebook, find this line:
```python
API_KEY = "YOUR_GEMINI_API_KEY_HERE"
```

Replace it with your actual API key:
```python
API_KEY = "AIzaSyB1234567890abcdef..."  # Your actual key here
```

### Step 5: Run the Notebook

1. Run all cells in the notebook
2. Choose your interaction mode:
   - **Option 1**: Start Interactive Chat
   - **Option 2**: Run Demo with Sample Responses
   - **Option 3**: View System Prompt

## Usage

### Starting a Conversation

```python
# Run the main function
run_poetic_chat()
```

### Chatting with Luna

Simply type your message when prompted:
```
💭 You: I had a tough day at work
```

Luna will respond with a personalized poem based on your emotional state.

### Exiting the Chat

Type any of these commands to end gracefully:
- `goodbye`
- `bye`
- `exit`
- `quit`

Or press `Ctrl+C` for immediate stop.

## How It Works

### 1. **Prompt Engineering**
The chatbot uses advanced prompt engineering to maintain Luna's poetic personality:
- Detailed system prompt defining character traits
- Emotional mapping (happy → sunlight, sad → rain)
- Literary device guidelines (metaphor, alliteration)
- Consistent tone and structure rules

### 2. **Emotion Detection**
Analyzes user input for emotional context:
```python
emotions = ['happy', 'sad', 'anxious', 'tired', 'confused', 'peaceful']
```

### 3. **Response Generation**
Combines emotion analysis with Gemini AI to create contextually appropriate poetry.

### 4. **Typing Animation**
Simulates real-time composition with:
- Variable speeds based on response length
- Realistic pauses at punctuation
- Dynamic visual effects

## 📊 API Usage Limits

### Free Tier (Gemini API):
- **15 requests per minute**
- **1,500 requests per day**
- **No credit card required**

**Daily limits reset at midnight UTC (5:30 AM IST for India)**

Perfect for personal projects, testing, and learning!

## Project Structure

```
poetic-personality-chatbot/
│
├── poetic_chatbot.ipynb          # Main Jupyter notebook
├── project_documentation.docx    # Detailed project report
├── README.md                      # This file
└── sample_conversations/          # Example chat histories
    └── example_chat.json
```

## Advanced Features

### Save Conversation History
```python
save_conversation_history(chatbot, "my_poetry_session.json")
```

### Analyze Poetry Patterns
```python
analyze_poetry_patterns(chatbot)
```

### Demo Mode
```python
demo_poetic_responses()
```

## Learning Objectives

This project demonstrates:
- **Prompt Engineering**: Crafting effective AI prompts for specific personalities
- **API Integration**: Working with modern LLM APIs (Gemini)
- **UI/UX Design**: Creating engaging user interfaces
- **Emotion AI**: Building emotionally intelligent applications
- **Creative AI**: Exploring AI's capacity for artistic expression

## Troubleshooting

### Common Issues:

**"API Key Error"**
- Ensure you've replaced `YOUR_GEMINI_API_KEY_HERE` with your actual key
- Check that your API key is active in Google AI Studio

**"Rate Limit Exceeded"**
- Wait 1 minute for per-minute limits
- Wait until midnight UTC for daily limit reset

**"Module Not Found"**
- Run the installation cell: `!pip install google-generativeai`
- Restart the runtime if needed

**Typing Animation Not Working**
- Ensure you're running in Google Colab (not local Jupyter)
- Check IPython display compatibility

## Acknowledgments

- Google Gemini Team for providing the powerful AI API
- The open-source community for inspiration and tools
- All the poets who've inspired Luna's creative spirit

---

<div align="center">

**Made with love for poetry**

*"Where every word becomes a verse, and every thought transforms into poetry..."*

</div>
