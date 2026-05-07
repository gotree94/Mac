# Mac

https://youtu.be/mba8cnGcgqE


## 1. https://brew.sh

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
```
gotree94@gotree94ui-MacBookPro ~ % brew install git
zsh: command not found: brew
gotree94@gotree94ui-MacBookPro ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
Password:
==> This script will install:
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew
==> The following new directories will be created:
/usr/local/bin
/usr/local/etc
/usr/local/include
/usr/local/lib
/usr/local/sbin
/usr/local/share
/usr/local/var
/usr/local/opt
/usr/local/share/zsh
/usr/local/share/zsh/site-functions
/usr/local/var/homebrew
/usr/local/var/homebrew/linked
/usr/local/Cellar
/usr/local/Caskroom
/usr/local/Frameworks
==> The Xcode Command Line Tools will be installed.

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /bin/mkdir -p /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /bin/chmod ug=rwx /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /bin/chmod go-w /usr/local/share/zsh /usr/local/share/zsh/site-functions
==> /usr/bin/sudo /usr/sbin/chown gotree94 /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /usr/bin/chgrp admin /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /bin/mkdir -p /usr/local/Homebrew
==> /usr/bin/sudo /usr/sbin/chown -R gotree94:admin /usr/local/Homebrew
==> Searching online for the Command Line Tools
==> /usr/bin/sudo /usr/bin/touch /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> Installing Command Line Tools for Xcode-16.4
==> /usr/bin/sudo /usr/sbin/softwareupdate -i Command\ Line\ Tools\ for\ Xcode-16.4
Software Update Tool

Finding available software

Downloading Command Line Tools for Xcode
Downloaded Command Line Tools for Xcode
Installing Command Line Tools for Xcode
Done with Command Line Tools for Xcode
Done.
==> /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
==> /usr/bin/sudo /bin/rm -f /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> Downloading and installing Homebrew...
remote: Enumerating objects: 331229, done.
remote: Counting objects: 100% (646/646), done.
remote: Compressing objects: 100% (271/271), done.
remote: Total 331229 (delta 503), reused 419 (delta 375), pack-reused 330583 (from 4)
remote: Enumerating objects: 55, done.
remote: Counting objects: 100% (33/33), done.
remote: Total 55 (delta 33), reused 33 (delta 33), pack-reused 22 (from 1)
==> Updating Homebrew...
==> Downloading https://ghcr.io/v2/homebrew/core/portable-ruby/blobs/sha256:f2bc4c3b081b09d7dcca97a8b8c5e102116e6ba68a5c118d6d961cf33b3162ec
############################################################################################################ 100.0%
==> Pouring portable-ruby-4.0.3.catalina.bottle.tar.gz
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these commands in your terminal to add Homebrew to your PATH:
    echo >> /Users/gotree94/.zprofile
    echo 'eval "$(/usr/local/bin/brew shellenv zsh)"' >> /Users/gotree94/.zprofile
    eval "$(/usr/local/bin/brew shellenv zsh)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh
```

```
eval "$(/usr/local/bin/brew shellenv zsh)"
```
```
gotree94@gotree94ui-MacBookPro ~ % brew -v
Homebrew 5.1.9
```

## 2. https://iterm2.com

```
brew install iterm2
```
```
gotree94@gotree94ui-MacBookPro ~ % brew install iterm2
==> Fetching downloads for: iterm2
✔︎ Cask iterm2 (3.6.10)                                                                  Verified     45.1MB/ 45.1MB
==> Installing Cask iterm2
==> Moving App 'iTerm.app' to '/Applications/iTerm.app'
🍺  iterm2 was successfully installed!
gotree94@gotree94ui-MacBookPro ~ % 
```

## 3.

2️⃣ zsh 설치 (설치되어있지 않은 경우에만 설치)
```
brew install zsh
```

3️⃣ Oh-My-Zsh 설치 스크립트
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

```
gotree94@gotree94ui-MacBookPro ~ % sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)" 

Cloning Oh My Zsh...
remote: Enumerating objects: 1462, done.
remote: Counting objects: 100% (1462/1462), done.
remote: Compressing objects: 100% (1399/1399), done.
remote: Total 1462 (delta 43), reused 1365 (delta 35), pack-reused 0 (from 0)
Receiving objects: 100% (1462/1462), 3.31 MiB | 23.19 MiB/s, done.
Resolving deltas: 100% (43/43), done.
From https://github.com/ohmyzsh/ohmyzsh
 * [new branch]      master     -> origin/master
branch 'master' set up to track 'origin/master'.
Switched to a new branch 'master'
/Users/gotree94

Looking for an existing zsh config...
Using the Oh My Zsh template file and adding it to /Users/gotree94/.zshrc.

         __                                     __   
  ____  / /_     ____ ___  __  __   ____  _____/ /_  
 / __ \/ __ \   / __ `__ \/ / / /  /_  / / ___/ __ \ 
/ /_/ / / / /  / / / / / / /_/ /    / /_(__  ) / / / 
\____/_/ /_/  /_/ /_/ /_/\__, /    /___/____/_/ /_/  
                        /____/                       ....is now installed!


Before you scream Oh My Zsh! look over the `.zshrc` file to select plugins, themes, and options.

• Follow us on X: https://x.com/ohmyzsh
• Join our Discord community: https://discord.gg/ohmyzsh
• Get stickers, t-shirts, coffee mugs and more: https://commitgoods.com/collections/oh-my-zsh

➜  ~ 
```

⌨️ iterm2 설정화면 진입
⌘ + ,

* profile -> session -> Status bar
* Appearance -> 

4️⃣ brew로 폰트 설치

https://github.com/madmalik/homebrew-cask-fonts

```
brew tap homebrew/cask-fonts
brew install font-fira-code
```

```
Last login: Thu May  7 08:53:21 on ttys001
➜  ~ brew tap homebrew/cask-fonts
Error: homebrew/cask-fonts was deprecated. This tap is now empty and all its contents were either deleted or migrated.
➜  ~ brew install font-fira-code
==> Fetching downloads for: font-fira-code
✔︎ Cask font-fira-code (6.2)                          Verified      2.5MB/  2.5MB
==> Installing Cask font-fira-code
==> Moving Font 'FiraCode-Bold.ttf' to '/Users/gotree94/Library/Fonts/FiraCode-B
==> Moving Font 'FiraCode-Light.ttf' to '/Users/gotree94/Library/Fonts/FiraCode-
==> Moving Font 'FiraCode-Medium.ttf' to '/Users/gotree94/Library/Fonts/FiraCode
==> Moving Font 'FiraCode-Regular.ttf' to '/Users/gotree94/Library/Fonts/FiraCod
==> Moving Font 'FiraCode-Retina.ttf' to '/Users/gotree94/Library/Fonts/FiraCode
==> Moving Font 'FiraCode-SemiBold.ttf' to '/Users/gotree94/Library/Fonts/FiraCo
==> Moving Font 'FiraCode-VF.ttf' to '/Users/gotree94/Library/Fonts/FiraCode-VF.
🍺  font-fira-code was successfully installed!
➜  ~
```

Color

```
https://iterm2colorschemes.com
```

```
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>Ansi 0 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.2</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.2</real>
		<key>Red Component</key>
		<real>0.2</real>
	</dict>
	<key>Ansi 1 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.5059</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.3176</real>
		<key>Red Component</key>
		<real>0.9098</real>
	</dict>
	<key>Ansi 10 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.6863</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8431</real>
		<key>Red Component</key>
		<real>0.6863</real>
	</dict>
	<key>Ansi 11 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.5216</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.9294</real>
		<key>Red Component</key>
		<real>0.8196</real>
	</dict>
	<key>Ansi 12 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.9294</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.698</real>
		<key>Red Component</key>
		<real>0.3922</real>
	</dict>
	<key>Ansi 13 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.9294</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.5961</real>
		<key>Red Component</key>
		<real>0.6392</real>
	</dict>
	<key>Ansi 14 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.8941</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.9294</real>
		<key>Red Component</key>
		<real>0.3804</real>
	</dict>
	<key>Ansi 15 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.9294</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.9294</real>
		<key>Red Component</key>
		<real>0.9294</real>
	</dict>
	<key>Ansi 2 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.5804</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8392</real>
		<key>Red Component</key>
		<real>0.4784</real>
	</dict>
	<key>Ansi 3 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.4549</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8157</real>
		<key>Red Component</key>
		<real>0.7176</real>
	</dict>
	<key>Ansi 4 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.8392</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.6275</real>
		<key>Red Component</key>
		<real>0.3529</real>
	</dict>
	<key>Ansi 5 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.8784</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.5647</real>
		<key>Red Component</key>
		<real>0.6039</real>
	</dict>
	<key>Ansi 6 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.8078</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8392</real>
		<key>Red Component</key>
		<real>0.3451</real>
	</dict>
	<key>Ansi 7 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.851</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.851</real>
		<key>Red Component</key>
		<real>0.851</real>
	</dict>
	<key>Ansi 8 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.502</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.502</real>
		<key>Red Component</key>
		<real>0.502</real>
	</dict>
	<key>Ansi 9 Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.5059</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.3176</real>
		<key>Red Component</key>
		<real>0.9098</real>
	</dict>
	<key>Background Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.1137</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.1137</real>
		<key>Red Component</key>
		<real>0.1137</real>
	</dict>
	<key>Bold Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.851</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.851</real>
		<key>Red Component</key>
		<real>0.851</real>
	</dict>
	<key>Cursor Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.6941</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8314</real>
		<key>Red Component</key>
		<real>0.6</real>
	</dict>
	<key>Cursor Guide Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.6941</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8314</real>
		<key>Red Component</key>
		<real>0.6</real>
	</dict>
	<key>Cursor Text Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.1137</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.1137</real>
		<key>Red Component</key>
		<real>0.1137</real>
	</dict>
	<key>Foreground Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.851</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.851</real>
		<key>Red Component</key>
		<real>0.851</real>
	</dict>
	<key>Selected Text Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.8078</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.8392</real>
		<key>Red Component</key>
		<real>0.3451</real>
	</dict>
	<key>Selection Color</key>
	<dict>
		<key>Alpha Component</key>
		<real>1</real>
		<key>Blue Component</key>
		<real>0.3294</real>
		<key>Color Space</key>
		<string>sRGB</string>
		<key>Green Component</key>
		<real>0.3255</real>
		<key>Red Component</key>
		<real>0.1412</real>
	</dict>
</dict>
</plist>
```

5️⃣ zsh 설정파일 열기
```
vi ~/.zshrc
```

6️⃣ zsh 설정파일 적용
```
source ~/.zshrc  
```

7️⃣ zsh 테마 수정파일 열기
```
vi ~/.oh-my-zsh/themes/agnoster.zsh-theme
```

8️⃣ prompt_newline
```
prompt_newline() {
  if [[ -n $CURRENT_BG ]]; then
    echo -n "%{%k%F{$CURRENT_BG}%}$SEGMENT_SEPARATOR
%{%k%F{blue}%}$SEGMENT_SEPARATOR"
  else
    echo -n "%{%k%}"
  fi

  echo -n "%{%f%}"
  CURRENT_BG=''
}
```

9️⃣ 명령어 하이라이팅
```
brew install zsh-syntax-highlighting
```

📌 M1이상
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
📌 intel Mac
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh

🔟 prompt_context 
```
prompt_context() {
  Custom (Random emoji)
  emojis=("⚡️" "🔥" "🇰 " "👑" "😎" "🐸" "🐵" "🦄" "🌈" "🍻" "🚀" "💡" "🎉" "🔑" "🚦" "🌙")
  RAND_EMOJI_N=$(( $RANDOM % ${#emojis[@]} + 1))
  prompt_segment black default "{하고싶은이름} ${emojis[$RAND_EMOJI_N]} "
}
```

🍎 단축키

⌨️ iterm2 설정화면 진입
⌘ + ,

⌨️ vi편집기 수정모드
cursor + i 

⌨️ vi편집기 파일 저장후 종료
ESC + :wq

⌨️ iterm2 상하/좌우 분할
⌘ + d / ⌘ + ⇧ + d

## brew install yarn




