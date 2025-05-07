# AI-Voice-Assistant
A blazing fast voice assistant that responds in under 1 second. Built with Node.js and WebSockets, it provides natural, uninterrupted voice interaction by combining top-tier AI and speech technologies.

- Lightning-Fast Response (<1s): Real-time processing powered by Groq's ultra-fast inference.
- Truly Conversational: Interrupt the assistant mid-response — it actually listens and adapts.
- Memory-Enabled: Maintains context by remembering past conversations for more coherent dialogue.
- Flexible AI Model Support: Choose between LLaMA 3 (70B/8B) or Gemma 7B models.
- Natural Voice Interaction:
- Speech-to-Text (STT): Powered by Deepgram for accurate real-time transcription.
- Text-to-Speech (TTS): Outputs lifelike voice using either PlayHT or Neets.
- Voice Commands: Simply say "Disconnect" to stop the assistant.
- Modular + Open Source: Easily extend with new models, TTS/STT providers, or custom logic.

Clone the repository:
- git clone https://github.com/xriddin/real-time-AI-voice-assistant.git
  cd real-time-AI-voice-assistant

Install dependencies:
- npm install

Create a .env file and configure your API keys:
-  You can get these keys from their respective platforms:
   - Groq: https://console.groq.com/keys
   - Deepgram: https://console.deepgram.com
   - PlayHT: https://play.ht
   - Neets: https://neets.ai/studio
     
Run the assistant:
- npm run start



