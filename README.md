# Awesome-openAI
A curated list of all things awesome about OpenAI - the research company behind ChatGPT

<img src="banner.png" />

### OpenAI General Resources
<ul>
  <li><a href="https://beta.openai.com/">OpenAI Overview</a></li>
  <li><a href="https://beta.openai.com/docs/introduction">OpenAI API Documentation</a></li>
  <li><a href="https://beta.openai.com/examples">OpenAI Examples</a></li>
  <li><a href="https://beta.openai.com/playground">OpenAI Playground</a></li>
</ul>

### Quick Start
<ul>
  <li><a href="https://beta.openai.com/docs/quickstart">OpenAI Quick Start</a></li>
  <li><a href="https://github.com/openai/openai-quickstart-node">OpenAI Quick Start app</a></li>
</ul>

### Models
<ul>
  <li><a href="https://beta.openai.com/docs/models/gpt-3">GPT-3</a></li>
  <li><a href="https://beta.openai.com/docs/models/codex">Codex</a></li>
  <li><a href="https://beta.openai.com/docs/models/content-filter">Content filter</a></li>
</ul>

### Guides on building applications
<ul>
  <li><a href="https://beta.openai.com/docs/guides/completion">Text completioan</a></li>
  <li><a href="https://beta.openai.com/docs/guides/images">Image generation</a></li>
  <li><a href="https://beta.openai.com/docs/guides/code">Code completioan</a></li>
  <li><a href="https://beta.openai.com/docs/guides/embeddings">Embeddings</a></li>
  <li><a href="https://beta.openai.com/docs/guides/fine-tuning">Fine-tuning</a></li>
</ul>

### Popular Applications
<ul>
  <li><a href="https://chat.openai.com/">ChatGPT - Official app</a></li>
  <li><a href="https://beta.openai.com/docs/guides/images">Dalle - Official Image generation app</a></li>
  <li><a href="https://openai.com/blog/whisper/">Whisper - Oficial speech recognition app </a></li>
  <li><a href="https://github.com/transitive-bullshit/chatgpt-twitter-bot">Twitter bot </a></li>
  <li><a href="https://github.com/franalgaba/chatgpt-telegram-bot-serverless">Serverless Telegram bot</a></li>
  <li><a href="https://github.com/Jaykef/OpenAI-ImageGeneration-Vue3">Dalle clone - Vue3</a></li>
  <li><a href="https://github.com/vincelwt/chatgpt-mac">Mac menubar ChatGPT App</a></li>
  <li><a href="https://github.com/cesarhuret/docGPT">Google docs bot - ChatGPT as Addon in Google docs</a></li>
  <li><a href="https://github.com/m1guelpf/chatgpt-discord">Dicord bot - ChatGPT for discord</a></li>
</ul>

### Apps Utilizing OpenAI API with Frontend Frameworks/Libraries
<ul>
  <li><a href="https://github.com/openai/openai-quickstart-node">OpenAI Quick Start - React</a></li>
  <li><a href="https://github.com/Jaykef/OpenAI-ImageGeneration-Vue3">Dalle Clone - Vue3, vite, pinia</a></li>
</ul>

### VSCode Extensions
<ul>
  <li><a href="https://marketplace.visualstudio.com/items?itemName=dogukanakkaya.chatgpt-code">OpenAI Helper - helps you use OpenAI tools in Visual Studio Code</a></li>
  <li><a href="https://marketplace.visualstudio.com/items?itemName=JayBarnes.chatgpt-vscode-plugin">ChatGPT VScode Plugin</a></li>
  <li><a href="https://marketplace.visualstudio.com/items?itemName=kiranshah.chatgpt-helper">ChatGPT</a></li>
  
</ul>

### API References
To install the official Python bindings, run the following command:
```
pip install openai
```
To install the official Node.js library, run the following command in your Node.js project directory:

```
npm install openai
```
#### Authentication
The OpenAI API uses API keys for authentication. Visit your <a href="https://beta.openai.com/account/api-keys">API Keys</a>  page to retrieve the API key you'll use in your requests.

Remember that your API key is a secret! Do not share it with others or expose it in any client-side code (browsers, apps). Production requests must be routed through your own backend server where your API key can be securely loaded from an environment variable or key management service.

All API requests should include your API key in an Authorization HTTP header as follows:
```
Authorization: Bearer YOUR_API_KEY
```


