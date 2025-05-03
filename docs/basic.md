# macOS ターミナルコマンド集

## 基本的なナビゲーション

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>pwd</code></td>
      <td>現在のディレクトリを表示</td>
    </tr>
    <tr>
      <td><code>ls</code></td>
      <td>ディレクトリ内のファイルとフォルダを表示</td>
    </tr>
    <tr>
      <td><code>ls -l</code></td>
      <td>詳細表示</td>
    </tr>
    <tr>
      <td><code>ls -la</code></td>
      <td>隠しファイルも含めて詳細表示</td>
    </tr>
    <tr>
      <td><code>ls -lh</code></td>
      <td>ファイルサイズを読みやすい形式で表示</td>
    </tr>
    <tr>
      <td><code>cd /path/to/directory</code></td>
      <td>指定したディレクトリに移動</td>
    </tr>
    <tr>
      <td><code>cd ~</code></td>
      <td>ホームディレクトリに移動</td>
    </tr>
    <tr>
      <td><code>cd ..</code></td>
      <td>一つ上のディレクトリに移動</td>
    </tr>
    <tr>
      <td><code>cd -</code></td>
      <td>直前にいたディレクトリに移動</td>
    </tr>
  </tbody>
</table>

## ファイル操作

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>touch filename.txt</code></td>
      <td>ファイルの作成</td>
    </tr>
    <tr>
      <td><code>mkdir directory_name</code></td>
      <td>ディレクトリの作成</td>
    </tr>
    <tr>
      <td><code>mkdir -p parent/child/grandchild</code></td>
      <td>親ディレクトリも同時に作成</td>
    </tr>
    <tr>
      <td><code>cp source.txt destination.txt</code></td>
      <td>ファイルのコピー</td>
    </tr>
    <tr>
      <td><code>cp -R source_dir destination_dir</code></td>
      <td>ディレクトリをコピー</td>
    </tr>
    <tr>
      <td><code>mv old_name.txt new_name.txt</code></td>
      <td>ファイル/ディレクトリの名前変更</td>
    </tr>
    <tr>
      <td><code>mv file.txt /path/to/destination/</code></td>
      <td>ファイル/ディレクトリの移動</td>
    </tr>
    <tr>
      <td><code>rm filename.txt</code></td>
      <td>ファイルの削除</td>
    </tr>
    <tr>
      <td><code>rm -rf directory_name</code></td>
      <td>ディレクトリを再帰的に削除（注意して使用）</td>
    </tr>
    <tr>
      <td><code>cat filename.txt</code></td>
      <td>ファイルの内容を表示</td>
    </tr>
    <tr>
      <td><code>less filename.txt</code></td>
      <td>スクロール可能な表示（qで終了）</td>
    </tr>
    <tr>
      <td><code>head -n 10 filename.txt</code></td>
      <td>先頭10行を表示</td>
    </tr>
    <tr>
      <td><code>tail -n 10 filename.txt</code></td>
      <td>末尾10行を表示</td>
    </tr>
    <tr>
      <td><code>tail -f filename.txt</code></td>
      <td>ファイルの更新をリアルタイムで表示</td>
    </tr>
  </tbody>
</table>

## ファイル検索

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>find /path/to/search -name "filename.txt"</code></td>
      <td>ファイル名で検索</td>
    </tr>
    <tr>
      <td><code>find . -name "*.txt"</code></td>
      <td>現在のディレクトリから全てのtxtファイルを検索</td>
    </tr>
    <tr>
      <td><code>grep "search_text" filename.txt</code></td>
      <td>ファイル内のテキスト検索</td>
    </tr>
    <tr>
      <td><code>grep -r "search_text" /path/to/directory</code></td>
      <td>ディレクトリ内を再帰的に検索</td>
    </tr>
  </tbody>
</table>

### ファイル内のテキスト検索
grep "search_text" filename.txt
grep -r "search_text" /path/to/directory    # ディレクトリ内を再帰的に検索
