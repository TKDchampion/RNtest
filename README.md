# ReactNative 開發環境(Mac + ios)
###### tags: `reactmaker`

![](https://i.imgur.com/Nzt7Gob.jpg)


所需要安裝：
- [Homebrew](https://brew.sh/)
- [Node](https://nodejs.org/en/)
- [yarn](https://yarnpkg.com/en/)
- [Xcode](https://developer.apple.com/download/)
- [Ｗatchman](https://facebook.github.io/watchman/docs/install.html)
- React-Native-Cli


## Homebrew
Mac系統的包管理器，用於安裝NodeJS和一些其他相關套件
``` 
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Node
一般在Mac我們使用Homebrew來安裝，RN目前需要NodeJS 5.0或更高版本。
```
$ brew install node
```
### p.s. 
- 如brew所安裝的node有問題可直接下載官網的

## yarn
可用來代替npm的工具，加速node模組的下載
```
$ npm install -g yarn
```

## react-native-cli
React Native的命令行工具用於執行創建、更新項目、打包...等服務。
```
$ npm install -g react-native-cli
```
or
```
$ yarn add react-native-cli
```

## Xcode
React Native目前只支援Xcode 8.0或更高版本。可以到App Store或是到Apple官網下載。

## Watchman
讓packager可以快速捕捉文件的變化從而實現實時刷新。
```
$ brew install watchman
```

## Build
```javascript
$ react-native init Project     //create project
$ cd Project
$ react-native run-ios          //ios emulator
```
### p.s. 
- 進入專案後須先npm install or yarn
- 在iOS Emulator中按下⌘-R就可以刷新APP
