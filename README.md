#前端工程訓練：<br>npm,bower,yo,gulp,webpack 應用實戰

前端工程領域在近幾年可謂百家爭鳴、百花齊放，越來越多的前端框架、前端套件，甚至前端工具，皆如雨春筍的冒出頭，一下子 grunt 又一下子 gulp，一下子 browserify 又一下子 webpack 的，好不讓人眼花撩亂、霧裡看花啊！身為一個前端工程師，所要面對的不僅僅是多如牛毛的技術細節，還要應付各式各樣的煩悶又重複的工作，效能調校、圖片壓縮、打包JS/CSS檔案、套件版本管理與升級、... 全部都要會，沒有強烈的熱情著實難以為繼。

市面上各式前端工具此消彼長，優劣勝敗各有所見，正所謂前端工具的重點不在量多，而在於質精，能搭配出一套好用的前端工具箱，是身為一個前端工程師不可或缺的技能之一。

本課程精選5套優質的前端工具，經由系統化的課程設計與實例演練，預計讓學員能在最短時間內掌握前端流程管理的精隨之處，學會這些工具所改善的不僅僅是提升效率與降低錯誤而已，更重要的是讓前端的工作變得更有趣，也進而讓前端人員專注於核心問題，不斷創造價值。

## 上課注意事項

- 學員**需自備筆電**，且須事先安裝好實作環境
- 學員的筆電建議使用 Windows 或 Mac OS X 作業系統
    - 若為 Windows 作業系統建議使用 Windows 7 以上版本
    - 若為 Mac OS X 作業系統建議使用 Mac OS X 10.6 以上版本
- 教室會**提供 WiFi 網路**與**電源插座**，
    - 如果有 3G 吃到飽的學員，建議還是自行攜帶，以備不時之需。

## 實作環境說明

為了能讓大家能在課堂上順利地進行實作，請在上課前把需要的軟體全部安裝好，以下是安裝的相關軟體與安裝步驟與說明，如果安裝過程有遇到任何問題，請上本班專屬 Facebook 社團發問。

## 打造前端工程師的開發環境 (Windows)

### [ 作業系統 ]

- Windows 7 以上版本 (更新到最新 Service Pack 版本)

### [ 瀏覽器 ]

- [Google Chrome](http://www.google.com/intl/zh-TW/chrome/)
  - [AngularJS Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk)
  - [Angular Scope Inspector](https://chrome.google.com/webstore/detail/angular-scope-inspector/aaglpchhlnofjbbpopfdfgllfkhnljnl)
  - [ng-inspector for AngularJS](http://ng-inspector.org/)
  - [AngularJS Batarang (Stable) v0.4.3](https://chrome.google.com/webstore/detail/angularjs-batarang-stable/niopocochgahfkiccpjmmpchncjoapek)


### [ 開發工具 ]

- [Visual Studio Community 2013](http://go.microsoft.com/fwlink/?LinkId=532495&clcid=0x409)
- [Visual Studio 2013 語言套件 - 繁體中文](http://go.microsoft.com/fwlink/?LinkID=320680&clcid=0x404)
  - [Web Essentials 2013](http://vswebessentials.com/)
  - [VSCommands for Visual Studio 2013](http://vscommands.squaredinfinity.com/features)

### [ 文字編輯器 ]

- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text 3](http://www.sublimetext.com/3)
  - [Package Control - the Sublime Text package manager](https://packagecontrol.io/installation)<br>
  請依照上述網址的說明進行安裝，重開 Sublime Text 3 之後即可安裝以下套件：
    * AngularJS
    * AngularJS Snippets
    * AutoFileName
  - [The Will Will Web | Sublime Text 3 新手上路：必要的安裝、設定與基本使用教學](http://blog.miniasp.com/post/2014/01/07/Useful-tool-Sublime-Text-3-Quick-Start.aspx)
- [Brackets](http://brackets.io/)
- [Atom](http://atom.io/)

### [ 套件管理器 ]

- [Chocolatey — The package manager for Windows](https://chocolatey.org/)

  ```
  @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
  ```

### [ 安裝必要工具 ]

- 開啟「命令提示字元」視窗 (以系統管理員身分開啟)，依序執行以下指令：

  ```
  cinst git -y
  cinst tortoisegit -y
  cinst nodejs -y
  cinst python2 -y
  cinst ruby -y

  gem update --system
  gem install compass

  setx GYP_MSVS_VERSION 2013 /M
  setx GYP_MSVS_VERSION 2013
  ```

	- [Git for Windows](https://git-for-windows.github.io/)
	- [TortoiseGit – Windows Shell Interface to Git](https://tortoisegit.org/)
	- [Node.js](https://nodejs.org/)
	- [Python](https://www.python.org/)
	- [Ruby](https://www.ruby-lang.org/)


- 重新開啟「命令提示字元」視窗 (以系統管理員身分開啟)，依序執行以下指令：

  ```
  npm install -g bower gulp yo webpack webpack-dev-server browser-sync rimraf

  npm install -g generator-gulp-webapp
  npm install -g generator-gulp-angular@0.12.1
  npm install -g generator-gulp-angular-subtask@0.9.1
  npm install -g generator-angular-webpack
  npm install -g generator-hottowel
  npm install -g generator-aspnet
  ```

### [ 參考資源整理 ]

- [前端工程師如何在 Windows 安裝自動化流程工具](https://www.youtube.com/watch?v=v1lyWPARQXg) (YouTube)


## 打造前端工程師的開發環境 (Mac OS X)

### [ 作業系統 ]

- Mac OS X 10.6 以上版本

### [ 瀏覽器 ]

- [Google Chrome](http://www.google.com/intl/zh-TW/chrome/)
  - [AngularJS Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk)
  - [Angular Scope Inspector](https://chrome.google.com/webstore/detail/angular-scope-inspector/aaglpchhlnofjbbpopfdfgllfkhnljnl)
  - [ng-inspector for AngularJS](http://ng-inspector.org/)
  - [AngularJS Batarang (Stable) v0.4.3](https://chrome.google.com/webstore/detail/angularjs-batarang-stable/niopocochgahfkiccpjmmpchncjoapek)

### [ 文字編輯器 ]

- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text 3](http://www.sublimetext.com/3)
  - [Package Control - the Sublime Text package manager](https://packagecontrol.io/installation)
  請依照上述網址的說明進行安裝，重開 Sublime Text 3 之後即可安裝以下套件：
    * AngularJS
    * AngularJS Snippets
    * AutoFileName
  - [The Will Will Web | Sublime Text 3 新手上路：必要的安裝、設定與基本使用教學](http://blog.miniasp.com/post/2014/01/07/Useful-tool-Sublime-Text-3-Quick-Start.aspx)
- [Brackets](http://brackets.io/)
- [Atom](http://atom.io/)

### [ 套件管理器 ]

- [Homebrew — The missing package manager for OS X](http://brew.sh/)
	- 安裝過程會要求你安裝 [Xcode](https://itunes.apple.com/us/app/xcode/id497799835) (完整安裝)
	- 需要 bash 或 zsh 的 Shell 環境
	- 套件搜尋網站: [Search Brew](http://searchbrew.com/)

### [ 安裝必要工具 ]

- 開啟 Terminal 視窗，依序執行以下指令：

  ```
  brew install git
  brew install node

  npm install -g bower gulp yo webpack webpack-dev-server browser-sync rimraf

  npm install -g generator-gulp-webapp
  npm install -g generator-gulp-angular@0.12.1
  npm install -g generator-gulp-angular-subtask@0.9.1
  npm install -g generator-angular-webpack
  npm install -g generator-hottowel
  ```

- 若覺得每次安裝 global npm 模組都要打 sudo 很麻煩的話，可以建議用以下命令重裝 node 與 npm<br>
  參考文章：[How to use npm global without sudo on OSX](http://www.johnpapa.net/how-to-use-npm-global-without-sudo-on-osx/)

  ```
  brew install node --without-npm
  mkdir "${HOME}/.npm-packages"
  echo NPM_PACKAGES="${HOME}/.npm-packages" >> ${HOME}/.bashrc
  echo prefix=${HOME}/.npm-packages >> ${HOME}/.npmrc
  curl -L https://www.npmjs.org/install.sh | sh
  echo NODE_PATH=\"\$NPM_PACKAGES/lib/node_modules:\$NODE_PATH\" >> ${HOME}/.bashrc
  echo PATH=\"\$NPM_PACKAGES/bin:\$PATH\" >> ${HOME}/.bashrc
  echo source "~/.bashrc" >> ${HOME}/.bash_profile
  source ~/.bashrc
  ```

- [Fixing npm permissions | npm Documentation](https://docs.npmjs.com/getting-started/fixing-npm-permissions#fixing-npm-permissions)


### [ 參考資源整理 ]

- [前端工程工具安裝 For OSX](https://frontend-prepare.hackpad.com/-For-OSX-9Vw9SWYOWEK)


## 常見問題解答

1. 使用 npm 安裝套件時都會出現「**指定的路徑、檔名，或是兩者都太長。完整的檔名必須少於 260 個字元，並且目錄名稱必須少於 248 個字元**」錯誤訊息怎麼辦？
	- 參見 [如何在 Windows 平台變更 Node.js / npm 全域模組的預設安裝路徑](http://blog.miniasp.com/post/2015/09/02/Change-npm-default-global-installation-directory-for-nodejs-modules-in-Windows.aspx) 文章。
2. 請問我公司因為需要設定代理伺服器 (Proxy Server) 才能上網，請問要做那些設定才好呢？
	- 參見 [如何在強制使用代理伺服器的環境下設定 git, npm, bower, gem, ionic 工具](http://blog.miniasp.com/post/2015/09/03/proxy-settings-for-git-npm-bower-gem-ionic.aspx) 文章。
