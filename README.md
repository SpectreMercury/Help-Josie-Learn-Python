# Help Josie Learn Python

# 目录

- 基础
  - [Lesson. 1](## Lesson 1 - Bash)
  - [Lesson. 2](## Lesson 2 - Python and Jupyter)

## Lesson 1 - Bash

### Install Environment

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

- [ ] Generate ssh keys

```bash
# 生成密钥
ssh-keygen -t ed25519 -C "你的邮箱@example.com"

# 启动ssh-agent
eval "$(ssh-agent -s)"

# 添加SSH私钥到ssh-agent
ssh-add ~/.ssh/id_ed25519

# 复制你的ssh公钥
pbcopy < ~/.ssh/id_ed25519.pub
```

- [ ] Set Github Environment

```bash
git config --global user.name "你的名字"
git config --global user.email "你的邮箱@example.com"

```

- [ ] Clone this project (By ssh not HTTPS)

```bash
git clone git@github.com:lee920217/Help-Josie-Learn-Python.git
```

- [ ] Trying to make some change

```
# Create a branch
git branch josiechange

# After change
git status # compare file change
git diff # check difference
git commit -m "Josie first change"
git push 

```

- [ ] Create a PR on github

Open Project [Help Josie Learn Python](https://github.com/lee920217/Help-Josie-Learn-Python), you will find a Green Button `Create Pull Request` to Create a merge request

