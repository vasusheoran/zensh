# Zensh

This is the zsh configuration for the Dreams of Autonomy YouTube Channel.

This configuration prioritizes zen and calm in order to reduce distractions and 
maintain momentum when working inside of the terminal.

# Installation
1. Install zsh
```bash
sudo apt install zsh
```

2. Install nerd font
```bash
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/JetBrainsMono.zip
mkdir ttf-jetbrains-mono-nerd
mv JetBrainsMono.zip ttf-jetbrains-mono-nerd 
sudo apt install unzip
unzip JetBrainsMono.zip
rm JetBrainsMono.zip
mkdir /usr/share/fonts/truetype/ttf-jetbrains-mono-nerd
sudo cp ttf-jetbrains-mono-nerd/*.ttf /usr/share/fonts/truetype/ttf-jetbrains-mono-nerd
```

3. Install fzf
```bash
sudo apt install fzf
```

4. Install zoxide
```bash
curl -sSfL https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | sh
```
