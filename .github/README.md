


- gh-pagesパッケージをインストール
npm install gh-pages --save-dev


package.jsonに以下を追加

  "homepage": "https://kanpanda.github.io/react-sample/",

    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"

readme.mdファイルが表示されないように、.githubファイルをルート配下につくり、readme.mdファイルを移動

npm run build

githubpagesの設定で,branchをgh-pagesに変更

しばらく待つ

表示されるはず

