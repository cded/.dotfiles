```
sudo apt install zsh   // or equivalent
```

```
chsh -s $(which zsh)  // switch shell to zsh
```

Clone this repo into HOME

```
git clone --recurse-submodules https://github.com/cded/.dotfiles
```

Install Nvm and sdkman (and others to come)

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

curl -s "https://get.sdkman.io" | bash
```

And finally copy the zsh profile into Home

```
cp .dotfiles/zsh/.zshrc .
```
