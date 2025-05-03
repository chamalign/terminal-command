## 圧縮・解凍

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>tar -czvf archive.tar.gz directory/</code></td>
      <td>gzipで圧縮</td>
    </tr>
    <tr>
      <td><code>tar -cjvf archive.tar.bz2 directory/</code></td>
      <td>bzip2で圧縮</td>
    </tr>
    <tr>
      <td><code>zip -r archive.zip directory/</code></td>
      <td>zipで圧縮</td>
    </tr>
    <tr>
      <td><code>tar -xzvf archive.tar.gz</code></td>
      <td>tar.gz解凍</td>
    </tr>
    <tr>
      <td><code>tar -xjvf archive.tar.bz2</code></td>
      <td>tar.bz2解凍</td>
    </tr>
    <tr>
      <td><code>unzip archive.zip</code></td>
      <td>zip解凍</td>
    </tr>
  </tbody>
</table>

## その他の便利なコマンド

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>open -a "TextEdit" filename.txt</code></td>
      <td>TextEditでファイルを開く</td>
    </tr>
    <tr>
      <td><code>open -a "Visual Studio Code" .</code></td>
      <td>VSCodeでカレントディレクトリを開く</td>
    </tr>
    <tr>
      <td><code>history</code></td>
      <td>コマンド履歴を表示</td>
    </tr>
    <tr>
      <td><code>!123</code></td>
      <td>履歴番号123のコマンドを実行</td>
    </tr>
    <tr>
      <td><code>!!</code></td>
      <td>直前のコマンドを実行</td>
    </tr>
    <tr>
      <td><code>sort filename.txt</code></td>
      <td>ファイルの内容をソート</td>
    </tr>
    <tr>
      <td><code>uniq filename.txt</code></td>
      <td>重複行を削除</td>
    </tr>
    <tr>
      <td><code>wc -l filename.txt</code></td>
      <td>行数をカウント</td>
    </tr>
    <tr>
      <td><code>sed 's/old/new/g' file</code></td>
      <td>テキスト置換</td>
    </tr>
    <tr>
      <td><code>alias ll='ls -la'</code></td>
      <td>コマンドのエイリアスを作成</td>
    </tr>
    <tr>
      <td><code>sudo command</code></td>
      <td>管理者権限でコマンドを実行</td>
    </tr>
  </tbody>
</table>

## 環境変数・シェル設定

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>echo $PATH</code></td>
      <td>PATHを表示</td>
    </tr>
    <tr>
      <td><code>export PATH=$PATH:/new/path</code></td>
      <td>PATHに追加</td>
    </tr>
    <tr>
      <td><code>nano ~/.zshrc</code></td>
      <td>zshの設定ファイルを編集（macOS Catalina以降のデフォルト）</td>
    </tr>
    <tr>
      <td><code>nano ~/.bash_profile</code></td>
      <td>bashの設定ファイルを編集（古いmacOS）</td>
    </tr>
    <tr>
      <td><code>source ~/.zshrc</code></td>
      <td>設定ファイルを再読み込み</td>
    </tr>
  </tbody>
</table>

## Homebrew (macOSのパッケージマネージャー)

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"</code></td>
      <td>Homebrewのインストール</td>
    </tr>
    <tr>
      <td><code>brew install package_name</code></td>
      <td>パッケージをインストール</td>
    </tr>
    <tr>
      <td><code>brew uninstall package_name</code></td>
      <td>パッケージをアンインストール</td>
    </tr>
    <tr>
      <td><code>brew update</code></td>
      <td>Brewを更新</td>
    </tr>
    <tr>
      <td><code>brew upgrade</code></td>
      <td>インストール済みパッケージを更新</td>
    </tr>
    <tr>
      <td><code>brew list</code></td>
      <td>インストール済みパッケージを表示</td>
    </tr>
    <tr>
      <td><code>brew search text</code></td>
      <td>パッケージを検索</td>
    </tr>
  </tbody>
</table>
