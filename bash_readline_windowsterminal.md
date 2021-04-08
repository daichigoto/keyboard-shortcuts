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

## 削除

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

## Windows Terminal キーとキー表記

|キー|キー表記|
|:---|:---|
|「ESC」|\e|
|「ESC」「ESC」|\e\e|
|「Home」|\e[H|
|「Insert」|\e[2~|
|「Delete」|\e[3~|
|「End」|\e[F|
|「Page Up」|\e[5~|
|「Page Down」|\e[6~|
|「F1」|\eOP|
|「F2」|\eOQ|
|「F3」|\eOR|
|「F4」|\eOS|
|「F5」|\eO15~|
|「F6」|\eO17~|
|「F7」|\eO18~|
|「F8」|\eO19~|
|「F9」|\eO20~|
|「F10」|\eO21~|
|「Alt」＋「Home」|\e[1;3H|
|「Alt」＋「Insert」|\e[2;3~|
|「Alt」＋「Delete」|\e[3;3~|
|「Alt」＋「End」|\e[1;3F|
|「Alt」＋「Page Up」|\e[5;3~|
|「Alt」＋「Page Down」|\e[6;3~|
|「Ctrl」＋「Home」|\e[1;5H|
|「Ctrl」＋「Insert」|\e[2;5~|
|「Ctrl」＋「Delete」|\e[3;5~|
|「Ctrl」＋「End」|\e[1;5F|
|「Ctrl」＋「Page Up」|\e[5;5~|
|「Ctrl」＋「Page Down」|\e[6;5~|
|「↑」|\e[A|
|「↓」|\e[B|
|「→」|\e[C|
|「←」|\e[D|
|「Alt」＋「↑」|\e[1;3A|
|「Alt」＋「↓」|\e[1;3B|
|「Alt」＋「→」|\e[1;3C|
|「Alt」＋「←」|\e[1;3D|
|「Ctrl」＋「↑」|\e[1;5A|
|「Ctrl」＋「↓」|\e[1;5B|
|「Ctrl」＋「→」|\e[1;5C|
|「Ctrl」＋「←」|\e[1;5D|
|貼り付け開始|\e[200~|
|クエリステータスレポート|\e[5n|
|クエリステータスレポート（応答）|\e[0n|
|「Backspace」|\C-?|
|「Ctrl」＋「Backspace」|\C-H|
|「Tab」|\C-I|
|「Enter」|\C-M|