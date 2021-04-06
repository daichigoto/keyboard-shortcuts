# bash readline ショートカットキー

## カーソル移動

|キー|操作|
|:---|:---|
|「→」|カーソルを1文字右へ移動。|
|「←」|カーソルを1文字左へ移動。|
|「Home」|カーソルを行頭へ移動。|
|「End」|カーソルを行末へ移動。|
|「Ctrl」＋「→」|カーソルを単語の末尾へ移動、すでに単語の末尾の場合は、次の単語の末尾へ移動。|
|「Ctrl」＋「←」|カーソルを単語の先頭へ移動、すでに単語の先頭の場合は、前の単語の先頭へ移動。|

## 削除(Windows)

##### .inpturcに追加する設定

	"\C-h": backward-kill-word	# Ctrl-Backspace
	"\e[1;5H": unix-line-discard	# Ctrl-Home
	"\e[1;5F": kill-line		# Ctrl-End

|キー|操作|
|:---|:---|
|「Backspace」|カーソルのひとつ左の文字を削除。|
|「Delete」|カーソルのある場所の文字を削除。|
|「Ctrl」＋「Backspace」|カーソルのひとつ左の文字から単語頭までを削除。|
|「Ctrl」＋「Delete」|カーソルから単語末までを削除。|
|「Ctrl」＋「Home」|カーソルのひとつ左の文字から行頭までを削除。|
|「Ctrl」＋「End」|カーソルから行末までを削除。|

## 削除(Mac)

##### .inpturcに追加する設定

	"\e\C-h": backward-kill-word	# ESC Backspace
	"\e\e[3~": kill-word		# ESC Delete

|キー|操作|
|:---|:---|
|「Backspace」|カーソルのひとつ左の文字を削除。|
|「Delete」|カーソルのある場所の文字を削除。|
|「ESC」「Backspace」|カーソルのひとつ左の文字から単語頭までを削除。|
|「ESC」「Delete」|カーソルから単語末までを削除。|
|「Ctrl」＋「u」|カーソルのひとつ左の文字から行頭までを削除。|
|「Ctrl」＋「k」|カーソルから行末までを削除。|
