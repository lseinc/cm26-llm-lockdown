# Setup local sandbox for running examples:

## instructions are for a MAC OS 

### Add Ollama
- install Ollama `brew install ollama`
- add start-ollama.sh 
```bash
#!/bin/bash
# Create authentication configuration directory
mkdir -p $HOME/.ollama/auth

# Generate API key
export OLLAMA_API_KEY=$(openssl rand -hex 32)
echo "OLLAMA_API_KEY=$OLLAMA_API_KEY" > $HOME/.ollama/auth/.env

# Set appropriate permissions
chmod 600 ~/.ollama/auth/.env

# Configure additional security settings
export OLLAMA_HOST="127.0.0.1:11434"  # Bind to localhost only
export OLLAMA_KEEP_ALIVE="5m"         # Limit model keep-alive time
export OLLAMA_MAX_LOADED_MODELS="2"   # Limit concurrent models
export OLLAMA_SECURE="1"

# Start Ollama server with authentication
ollama serve
```
---

### using IntelliJ
- install JDK 21 or higher
- install Kotlin Notebook
---

### using vscodium 
- install continue extension
- install vscodium `brew install --cask vscodium`
- install vscodium continue extension to run ai chats
- add model to continue model config
```yaml
models:
  - name: Super Secret
    provider: ollama
    model: qwen2.5:3b
    roles:
      - chat
    defaultCompletionOptions:
      # temperature controls the randomness of the completion. 
      temperature: 0.0
      # top p is the probability of word selection for output response
      topP: 0.95
      # top k is the wordiness of responses
      topK: 40
```
---
### Install Msty
- install Msty Studio from msty.io , free version
  (could use LMStudio or other chat tool)
- follow instructions and point to
  http://localhost:11434
- use OPENAPI_KEY=ollama #(not setup for demo)


