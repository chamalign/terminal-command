## システム情報・プロセス

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>uname -a</code></td>
      <td>システム情報を表示</td>
    </tr>
    <tr>
      <td><code>df -h</code></td>
      <td>ディスク使用状況を表示</td>
    </tr>
    <tr>
      <td><code>top</code></td>
      <td>プロセスとシステムリソース使用状況を表示（qで終了）</td>
    </tr>
    <tr>
      <td><code>ps aux</code></td>
      <td>実行中のプロセスを表示</td>
    </tr>
    <tr>
      <td><code>ps aux | grep name</code></td>
      <td>特定のプロセスを検索</td>
    </tr>
    <tr>
      <td><code>kill PID</code></td>
      <td>プロセスを終了</td>
    </tr>
    <tr>
      <td><code>killall process</code></td>
      <td>名前でプロセスを終了</td>
    </tr>
  </tbody>
</table>

## ネットワーク

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>ping example.com</code></td>
      <td>指定ホストへの接続を確認</td>
    </tr>
    <tr>
      <td><code>curl -I https://example.com</code></td>
      <td>HTTPヘッダーを取得</td>
    </tr>
    <tr>
      <td><code>wget https://example.com/file</code></td>
      <td>ファイルをダウンロード</td>
    </tr>
    <tr>
      <td><code>ssh user@hostname</code></td>
      <td>SSHでリモートサーバーに接続</td>
    </tr>
    <tr>
      <td><code>scp file.txt user@host:/path/</code></td>
      <td>SSHでファイルを転送</td>
    </tr>
    <tr>
      <td><code>ifconfig</code></td>
      <td>ネットワークインターフェースの情報表示</td>
    </tr>
    <tr>
      <td><code>netstat -an</code></td>
      <td>ネットワーク接続の状態表示</td>
    </tr>
  </tbody>
</table>

## パーミッション

<table>
  <thead>
    <tr>
      <th>コマンド</th>
      <th>説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>chmod 755 filename</code></td>
      <td>所有者に実行権限を追加</td>
    </tr>
    <tr>
      <td><code>chmod +x script.sh</code></td>
      <td>ファイルに実行権限を追加</td>
    </tr>
    <tr>
      <td><code>chmod -R 755 directory</code></td>
      <td>ディレクトリ内のすべてに適用</td>
    </tr>
    <tr>
      <td><code>chown user:group filename</code></td>
      <td>所有者変更</td>
    </tr>
  </tbody>
</table>
