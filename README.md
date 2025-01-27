# apps-on-my-mba
我在我的 MacBook Air m1 2020 上使用的應用程式和工具們

## Homebrew
到 [brew.sh](https://brew.sh) ，用裡面提供的指令安裝 Homebrew，之後就可以在終端機上安裝大部分的 Apps。

### 使用 Homebrew 範例

更新所有應用程式

```zsh
brew upgrade
```

安裝多個應用程式，套件名稱中間用空白隔開（例：firefox、Brave）

```zsh
brew install firefox brave-browser
```

解除安裝應用程式（例：brave-browser）

```zsh
brew uninstall brave-browser
```

搜尋應用程式在 brew 上的套件名稱（例：visual studio code）

```zsh
brew search visualstudiocode
```

## 好用的工具

- [Raycast](https://raycast.com) 內建的 Spotlight 很好用，但這個能安裝一堆擴充功能，更好用
- [mos](https://mos.caldis.me/) 把滑鼠滾輪滾動的動畫變滑順（因為蘋果故意把各家滑鼠的滾動動畫變卡，謝謝蘋果）
- [AeroSpace](https://github.com/nikitabobko/AeroSpace) + [JankyBorders](https://github.com/FelixKratz/JankyBorders) 如果你用過 i3 wm 的話
- [middleclick](https://github.com/artginzburg/MiddleClick-Sonoma) 觸控板的三指點擊作為中鍵點擊（關閉分頁的時候就不用瞄準超小的分頁關閉叉叉）
- [KeyClu](https://github.com/Anze/KeyCluCask) 我是設定成按住 cmd 鍵會彈出快捷鍵列表
- [威注音 vchewing](https://vchewing.github.io/README.html) 選項很多的注音輸入法，對我來說大幅提升注音輸入的使用體驗
- [Better Display](https://github.com/waydabber/BetterDisplay) 在 menubar 調整顯示器設定和各種跟顯示有關的選項，All-in-one
- [Kitty](https://sw.kovidgoyal.net/kitty/) 我目前使用的終端機，執行速度很快，支援顯示圖片以及 Nerd Fonts 字型的小圖標
- [Hiddenbar](https://apps.apple.com/us/app/hidden-bar/id1452453066?mt=12) 把 menubar 擠滿的東西隱藏起來

## GUI Apps 圖形介面的應用程式

- [MarkEdit](https://github.com/MarkEdit-app/MarkEdit?tab=readme-ov-file) Markdown 文件編輯器

## TUI Apps 文字介面的程式

文字介面的意思就是只能在終端機裡面打指令來操作，沒有漂亮的毛玻璃視窗背景或飛來飛去的動畫。
如果你覺得終端機是奇怪阿宅才會用的東西，那你應該親自試試看，這邊有很多應用程式比你想像中來得簡單易用，而且有意料之外實用的地方。
~~而最大的優點是用起來感覺很酷。~~

- [Homebrew](https://brew.sh) 比 App Store 好用的套件管理（就是應用程式商店的意思）
- git 不多解釋
- neovim 有時候要編輯一些 config 檔案，但沒有很想等 vscode 打開，~~並且用 vim 方式編輯文件感覺很酷~~
- [tealdeer](https://github.com/tealdeer-rs/tealdeer) 快速取得許多 TUI app 的使用範例（許多時候比閱讀 help 來的方便）
- [Starship](https://starship.rs) 把終端機上的提示字元（prompt）變成酷酷的樣子
- [Spicetify](https://spicetify.app) 把 Spotify 變成酷酷的樣子
- [yazi](https://github.com/sxyazi/yazi) 用 vim 的瀏覽方式瀏覽電腦上的檔案
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) 跟各種亂七八糟的 yt 影片線上下載工具一樣功能，但比較乾淨
- [zoxide](https://github.com/ajeetdsouza/zoxide) 跟 cd 一樣，但更方便
- [eza](https://github.com/eza-community/eza) 跟 ls 一樣，但比較酷
- [scrcpy](https://github.com/Genymobile/scrcpy) 有線連接 Android 手機後，在電腦上就能用滑鼠鍵盤操作手機，不需要什麼訂閱付費方案就能開心用。
- [ffmpeg](https://www.ffmpeg.org/) 把任何格式的多媒體轉成你需要的格式
- [imagemagick](https://www.imagemagick.org/) 快速調整圖片的工具

## brew 上無法下載的

- ~~[cheatsheet](https://cheatsheet-mac.en.softonic.com/mac) 按住 cmd 鍵就可以看目前應用程式的所有快捷鍵~~ 改用 KeyClu 了
- ~~[Caprine](https://github.com/sindresorhus/caprine) FB Messenger~~ 朋友群組搬家到 telegram 後就不用了
- [PixelPerfect 超解析度](https://github.com/cormiertyshawn895/PixelPerfect/) 讓 MacOS 上的 iPad 應用程式，以正常比例來顯示 UI
- [The Unarchiver](https://theunarchiver.com/) 滑鼠點兩下解壓縮任何格式的壓縮檔

## 參考和延伸閱讀

以上有很多是因為看過這些影片裡提到而知道的，但我無法完全記得哪些來自哪裡

### Snazzy Labs
- [Amazing FREE Mac Apps You Aren’t Using!](https://youtu.be/FxUk8gxzHI8?feature=shared)
- [Superb FREE Mac Apps You Aren’t Using!](https://youtu.be/sPPTZ2nX1C0?feature=shared)
- [Hidden FREE Mac Apps!](https://youtu.be/D2_8qJi2jpQ?feature=shared)

### A Better Computer
- [10 Mac apps I don't talk about enough](https://youtu.be/0aKBgzibssU?feature=shared)
- [10 amazing little features in 10 amazing Mac apps](https://youtu.be/PoPIEcsvjPM?feature=shared)
