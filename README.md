```bash

sudo apt install build-essential libssl-dev pkg-config

# If you need to push updates
# git clone git@github.com:chrisboyce/dotfiles.git ~/.dotfiles

# If read-only is OK
git clone https://github.com/chrisboyce/dotfiles.git ~/.dotter

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source "$HOME/.cargo/env"
cargo install cargo-binstall
cargo binstall rtx-cli
echo 'eval "$(rtx activate bash)"' >> ~/.bashrc


```
