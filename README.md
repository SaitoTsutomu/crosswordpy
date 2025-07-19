## No Hint Crossword Puzzle

語彙力と推理力で全5ステージをクリアしよう。

* 同じ文字は一度に入力可能
* クリアするとタイムを表示

## インストール

```
uv tool install crosswordpy
```

## プレイ

```
crosswordpy
```

## アンインストール

```
uv tool uninstall crosswordpy
```

## 別データで上書きする場合

もし、別データのURLがある場合は、以下のようにデータを上書きできます。

```
curl -L 該当URL -o crosswordpy_data.zip
unzip -o crosswordpy_data.zip -d ~/.local/share/uv/tools/crosswordpy/lib/python3.1?/site-packages/crosswordpy
rm crosswordpy_data.zip
```
