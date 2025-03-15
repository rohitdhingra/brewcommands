#Setting up brew environment:
cd /opt/homebrew/bin/
PATH=$PATH:/opt/homebrew/bin
echo export PATH=$PATH:/opt/homebrew/bin >> ~/.zshrc
brew doctor
# k6 install
brew install k6
