
# Local DeepSeek Chat

DeepSeek-R1 took the world of AI by storm. For the first time, we see a glimpse of AGI. Access this power at your fingertips, for whatever you want, privately. No data stored, nothing uploaded. Just you, the future, and anything you can dream of.

🔐 **100% Local, 100% Private**
- Zero cloud dependencies
- Your data never leaves your machine
- Full control over your AI experience

🚀 **Why This Matters**

- True decentralized AI
- Own your data, own your future
- Be part of the AGI revolution

## Installation and setup

**Setup Ollama**:
   ```bash
   # setup ollama on linux 
   curl -fsSL https://ollama.com/install.sh | sh
   # setup ollama on windows
   winget install Ollama.Ollama
   # pull the DeepSeek-R1 model
   ollama pull deepseek-r1 
   ```


**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install pydantic==2.10.1 chainlit ollama
   ```

**Run the app**:

   Run the chainlit app as follows:
   ```bash
   chainlit run app.py -w
   ```
