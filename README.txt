言語名：Python3
エディター：Visual Studio Code

データファイルは次のように作成
(単語) (よみがな)
(単語) (よみがな)
...

with open(ファイルの場所) as dictionary_file:
    word = dictionary_file.read()
    print(word)
ファイルの場所を各自変更してください

python3 task1.py
を実行
""単語IDを入力してください:""
と表示されたら半角数字でIDを入力
