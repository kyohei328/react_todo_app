# README  

### 各バージョン  

Ruby 2.7.7  
Ruby on Rails 6.1.7.6  
yarn 1.22.19  
React 18.2.0  

### 環境構築  
Command Line Tools のインストール  
```$ xcode-select --install```  
Homebrew のインストール  
```$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```  
Homebrew のアップデート  
```$ brew update```  
 rbenv のインストール  
```$ brew install rbenv```  
rbenv への PATH を通す  
```$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc```  
rbenv を使うために必要な「rbenv init -」コマンドを設定  
```$ echo 'eval "$(rbenv init -)"' >> ~/.zshrc```  
設定の反映  
```$ source ~/.zshrc```  
Ruby のインストール  
```$ rbenv install 2.7.7```  
システム全体で使う ruby のバージョンを指定  
```$ rbenv global 2.7.0```  
Bundler のインストール  
```$ gem install bundler```  
yarn のインストール  
```$ brew install yarn```  
rails のインストール  
```$ gem install rails -v 6.1.7.6```  
