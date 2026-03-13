Install Zsh, Oh My Zsh, and Powerlevel10k
sudo apt update && sudo apt install zsh -y
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k


autosuggestion 
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


cp [sourceFilePath] ~/.zshrc
cp [sourceFilePath] ~/.p10k.zsh

i.e.
cp ~/Desktop/zshrc_backup ~/.zshrc
cp ~/Desktop/p10k_backup ~/.p10k.zsh

