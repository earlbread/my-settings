# 맥북 세팅 정리

 - 애플 계정 설정 및 업데이트
 - 키보드 설정
 - 크롬 설치 및 동기화
 - iterm2 설치 - [iTerm2 Preference][]
 - Homebrew 설치
 - Fish shell 설치

 ```bash
 brew install fish
 ```

 - Xcode, Xcode developer tools 설치
 - .dotfiles 실행

 ```bash
 git clone https://github.com/earlbread/.dotfiles
 cd .dotfiles
 ./run.sh
 ```

 - Neovim 설치

 ```
 brew install neovim
 git clone https://github.com/earlbread/nvimrc.git
 cd nvimrc
 ./install.sh
 ```

 - Git user 설정

 ```bash
 git config --global user.name "Seunghun Lee"
 git config --global user.email waydi1@gmail.com
 git config --global core.editor nvim
 ```

 - PyCharm Professional 설치
 - Postman 설치
 - MySQLWorkbench 설치

[iTerm2 Preference]: https://raw.githubusercontent.com/earlbread/my-settings/master/com.googlecode.iterm2.plist
