# Help Josie Learn Python

## Lesson 1 - Bash

- [ ] Download & Install [iTerm2](https://iterm2.com/)
- [ ] Download & Install [oh-my-zsh](https://ohmyz.sh/) in iTerm2
- [ ] Download & Install [homebrew](https://brew.sh/) in iTerm2
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- [ ] Download & Install conda by `brew`
```
brew install --cask miniconda
```
- [ ] Trying to create a virtual environment
```
conda create --name myenv python=3.8
```
- [ ] Activate, Install package and Deactivate environment

### Activate
```bash
conda activate myenv
```

### Install package by conda
```bash
conda install numpy
```

### Deactivate 
```bash
conda deactivate myenv
```
