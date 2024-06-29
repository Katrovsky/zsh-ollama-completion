# zsh-ollama-completion

A Zsh plugin providing command completion for Ollama AI models management.

## Features

- Autocompletes Ollama commands
- Provides model name suggestions for relevant commands
- Enhances productivity when working with Ollama CLI

## Installation

### Using Oh-My-Zsh

1. Clone this repository in Oh-My-Zsh's plugins directory:
```sh
git clone https://github.com/Katrovsky/zsh-ollama-completion.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/ollama
```
2. Activate the plugin in `~/.zshrc`:
```sh
plugins=(... ollama)
```
3. Restart your shell or run:
```sh
source ~/.zshrc
```
## Usage

Once installed, the plugin will automatically provide command completion for Ollama. Type `ollama` followed by a space and press Tab to see available commands. For commands that work with models (like `run`, `pull`, `show`, `rm`, `cp`), pressing Tab after the command will suggest available model names.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
