# Rime 鼠须管小鹤双拼配置 

## 详细说明

[配置说明](https://thisiswangle.com/posts/2020-03-16-rime-flypy-2020/)

## 安装

0. brew cask install squirrel
1. cd ~/Library
2. mv Rime Rime.bak
3. git clone git@github.com:thisiswangle/oh-my-squirrel.git Rime
4. mv "/Library/Input Methods/Squirrel.app/Contents/SharedSupport/opencc/TSCharacters.ocd" "/Library/Input Methods/Squirrel.app/Contents/SharedSupport/opencc/TSCharacters.ocd.bak"
5. cp Rime/TSCharacters.ocd "/Library/Input Methods/Squirrel.app/Contents/SharedSupport/opencc"

