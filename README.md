# chat-with-openai
Let's have a conversation with ChatGPT by using STT and TTS technologies!

I really want to realize ambient intelligence that augument human abilities.

Hope you guys enjoy and cotribute this project!

# Environment
- [x] Raspberry Pi 4 Model B Rev 1.4
  - Memory: 8GB
  - OS: Dedian 10.9

# Set up
1. Install Python 3.10 (pyenv is useful)
1. `pip install requirements.txt`
1. `export OPENAI_API_KEY="<your API key>"` (direnv is useful)
1. `python whisper_chatgpt.py 2> /dev/null`

# Demo

```
pi@raspberrypi:~/workspace/chat-with-openai $ python whisper_chatgpt.py 2> /dev/null
# recording (5 sec) ...
# You >  Hi, this is Mike. Nice to meet you.
# ChatGPT >  Hello, Mike. Nice to meet you too. How can I assist you today?
# recording (5 sec) ...
# You >  I wanna improve my pronunciation.
# ChatGPT >  Great! Improving pronunciation involves a lot of practice and attention to detail. Let's start with some basics. Can you tell me which specific sounds you find difficult pronouncing?
# recording (5 sec) ...
```

