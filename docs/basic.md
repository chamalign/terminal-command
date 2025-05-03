# 現在のディレクトリを表示
pwd

# ディレクトリ内のファイルとフォルダを表示
ls
ls -l     # 詳細表示
ls -la    # 隠しファイルも含めて詳細表示
ls -lh    # ファイルサイズを読みやすい形式で表示

# ディレクトリの移動
cd /path/to/directory    # 指定したディレクトリに移動
cd ~                     # ホームディレクトリに移動
cd ..                    # 一つ上のディレクトリに移動
cd -                     # 直前にいたディレクトリに移動
ファイル操作
bash# ファイルの作成
touch filename.txt

# ディレクトリの作成
mkdir directory_name
mkdir -p parent/child/grandchild    # 親ディレクトリも同時に作成

# ファイルのコピー
cp source.txt destination.txt
cp -R source_dir destination_dir    # ディレクトリをコピー

# ファイル/ディレクトリの移動・名前変更
mv old_name.txt new_name.txt
mv file.txt /path/to/destination/

# ファイル/ディレクトリの削除
rm filename.txt
rm -rf directory_name    # ディレクトリを再帰的に削除（注意して使用）

# ファイルの内容を表示
cat filename.txt
less filename.txt        # スクロール可能な表示
head -n 10 filename.txt  # 先頭10行を表示
tail -n 10 filename.txt  # 末尾10行を表示
tail -f filename.txt     # ファイルの更新をリアルタイムで表示
ファイル検索
bash# ファイル名で検索
find /path/to/search -name "filename.txt"
find . -name "*.txt"     # 現在のディレクトリから全てのtxtファイルを検索

# ファイル内のテキスト検索
grep "search_text" filename.txt
grep -r "search_text" /path/to/directory    # ディレクトリ内を再帰的に検索
