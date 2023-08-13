# Help Josie Learn Python

## Lesson 1 - Bash

- [ ] Download & Install [iTerm2](https://iterm2.com/)
- [ ] Download & Install [oh-my-zsh](https://ohmyz.sh/) in iTerm2
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
- [ ] Download & Install [homebrew](https://brew.sh/) in iTerm2
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
> 直接安装brew的内容可能会有点卡顿，可以考虑清华镜像，这里是[教程](https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/)，稍微有一点复杂，有问题可以随时问我哈哈

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
```
conda activate myenv
```

### Install package by conda
```
conda install numpy
```

### Deactivate

```
conda deactivate myenv
```
