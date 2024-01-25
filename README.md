# audio_cli_command_cheatsheet

My audio DSP cheatsheet (mainly for macOS).

## Setup Steps

### 1. Make symlink to home dir

```bash
cd /path/to/repo
ln -s ./audio_cli_command_cheatsheet.txt ~/audio_cli_command_cheatsheet.txt
```

### 2. Make alias for command

```bash
vi ~/.zshrc

# In .zshrc
alias my_audio_command_cheatsheet="cat ~/audio_cli_command_cheatsheet.txt"
```
