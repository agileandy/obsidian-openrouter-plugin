# OpenRouter Chat for Obsidian

An Obsidian plugin that allows you to chat with a wide variety of AI models using [OpenRouter](https://openrouter.ai).

## Features

- Access to dozens of AI models including Claude, GPT, Gemini, Mistral, Llama, and more
- Free model support with clearly marked free options
- Model filtering and search by name or provider
- Web search capability for real-time information (supported by some models)
- Simple chat interface in the Obsidian sidebar
- Insert AI responses directly at cursor position in your notes
- Track response metrics for performance analysis

## Installation

### From Obsidian Community Plugins

1. Open Obsidian Settings
2. Go to "Community plugins" and disable "Safe mode"
3. Click "Browse" and search for "OpenRouter Chat"
4. Install the plugin and enable it

### Manual Installation

1. Download the latest release from the [releases page](https://github.com/agileandy/obsidian-openrouter-plugin/releases)
2. Extract the ZIP file into your Obsidian vault's `.obsidian/plugins/` directory
3. Enable the plugin in Obsidian settings under "Community plugins"

## Configuration & Usage

### 1. Setup API Key

- Get an API key from [OpenRouter](https://openrouter.ai/keys)
- Open plugin settings and enter your API key
- Your API key stays on your device and is only used to authenticate with OpenRouter

### 2. Select Models

- Choose your default model in the settings (Gemini 2.0 Flash is set as the default free option)
- Use the dropdown in the chat interface to switch between models for each conversation
- Navigate the models grouped by provider (OpenAI, Anthropic, Google, etc.)

### 3. Filter & Search Models

- Use the search box to find models by name or provider
- Toggle "Free models only" to see only free options
- Click the refresh button to update the model list from OpenRouter

### 4. Chat Interface

- Click the chat icon in the ribbon or use the command "Open OpenRouter Chat"
- Type your message in the input box
- Press Enter to send (or Shift+Enter for a new line)
- View the AI's response in the chat window
- Clear the chat with the "Clear Chat" button to start fresh

### 5. Copy Output to Clipboard

- Each assistant message includes a copy button (📋)
- Click the button to copy the entire message to your clipboard
- A checkmark (✓) will briefly appear to confirm the copy

### 6. Web Search

- Toggle the web search button (🌐) to enable real-time information lookup
- Note: This feature is only supported by some models and may incur additional costs
- When enabled, the AI can search the web to provide up-to-date information

### 7. Response Metrics

- Each response includes performance metrics
- View time to first token, total time, and token count
- Click the metrics button (📊) to see detailed information
- Use these metrics to compare performance between different models

## Default Model

The default model is set to **Google Gemini 2.0 Flash** (free), which offers a good balance of performance and accessibility for all users.

## Keyboard Shortcuts

- **Enter**: Send message
- **Shift+Enter**: Add new line in the input
- **Up Arrow**: View response metrics (when available)

## Support

- Visit [OpenRouter](https://openrouter.ai) for more information about available models
- For plugin issues, please file a GitHub issue on this repository
- For API-related questions, please refer to the [OpenRouter documentation](https://openrouter.ai/docs)

## License

This project is licensed under the GPL-3.0 License.
