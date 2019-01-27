プロトタイプなので、要テストです

【Ver0.393用】
CFLAG:2 > 0ではなく、CFLAG:1 > 0でした
ほとんど書き換えです

\ERB\口上
;変身前のかけ声
@KOJO_0_BATTLE_CHARA_TRANSFORMCALL
CALL TRANSFORM, 1
TRYCALL KOJO_0_COLOR
;変身時かけ声設定
IF CFLAG:(TARGET):4 == 1
	PRINTFORML 「%CSTR:TARGET:2%」
ELSE
	SELECTCASE RAND:10
		CASE 1
			PRINTFORML 「チェンジ」
		CASEELSE
			PRINTFORML 「変身」
	ENDSELECT
ENDIF


\ERB\コマンド類\COMF0.ERB
;変身
SIF CFLAG:1 < 1
	CALL TRANSFORM, 1



に変更、名乗りが無くても改行で適合されるようになりました。
ピクシィミサも、呼び出し口上を専用に振り分けしました。



【Ver0.392用】
;敵キャラに勝利
@KOJO_0__BATTLE_END_WIN_ENEMY
@KOJO_0_BATTLE_END_WIN_ENEMY

_が並んでいたので消しました



性格を豹変するテンプレートとテスト
500番に天野美沙緒（ピクシィミサ）を設定
COLOR設定のところで、変身して性格の設定で変更するようにした
呼び出すのは汎用なので、足りないところも多い