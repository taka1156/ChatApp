# my_chat_app

takaのチャットアプリです
(https://chatapp-f1e5d.firebaseapp.com/)

# 使用したもの
- HTML
- CSS
- JavaScript
- vue.js
- BootStrap4(CDN)
- Firebase(Twitter認証,hosting, realtime DB)

# その他素材
- Google Material Icons

    (https://material.io/resources/icons/?style=baseline)
- UnDraw

    (https://undraw.co/)

# 内容
Twitterアカウントを利用してチャットをするアプリです。<br>
- 2019/11/30<br>
    URLから直接チャットページに飛べるようにvue-routerの設定を変更<br>
- 2019/12/04<br>
    githubのセキュリティアラート対応(` js-yaml`関連)で`yarn audit`で確認した結果、`url-loader`と`css-loader`が対象とわかったので、それらを更新した。