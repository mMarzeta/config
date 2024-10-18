NVIM Config for real 10x devs.

It's modularized, originated from awesome https://github.com/nvim-lua/kickstart.nvim.

## Setting up tmux:

rm -rf ~/.tmux/plugins/tpm
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

chmod +x ~/.tmux/plugins/tpm/tpm
chmod +x ~/.tmux/plugins/tpm/scripts/install_plugins.sh

~/.tmux/plugins/tpm/bin/install_plugins

