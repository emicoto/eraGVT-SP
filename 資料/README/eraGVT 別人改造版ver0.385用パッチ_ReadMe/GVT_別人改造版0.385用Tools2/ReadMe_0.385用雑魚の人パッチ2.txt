【注意】
変更点が多いためTool1の「スラング」フォルダを空にしてから、上書きください

汎用関数@PRINT_RGBTEXT(ARGS:0,ARGS:1)を作成
ARGS:0に色、ARGS:2にPRINTFORM用の文字列を指定
指定した文字に色付をして変換する

@COLOR_T_SHAPE(ARGS:0,ARGS:1)
汎用関数@PRINT_RGBTEXT(ARGS:0,ARGS:1)を利用して触手の色を表現する関数

@T_STATUS_BCOLOR
触手ステータスや状態で色をどうするか返す関数

【変更点】

指摘のあったフェラチオの行動指定の部分の修正

SLANGを口語用と地の文様に分割
%SPOKENSLANG("名称")%	:口語での名称を簡単に返すためのショートカット
	@CALLSLANG（部位）を、@WRITTENSLANG（部位）に変更
	地の文の文語（WRITTEN）と、口上の口語（SPOKEN）で視覚的にわかるよう

%SLANG_N(TARGET)%	;地の文の乳首
	乳首なのに中にマウスのMを入れて書き換え忘れていたので修正

%SLANG_Labia(TARGET)%	;地の文の陰唇
	式の簡略を行うとエラーが起きるので、修正


戦闘時にパラメータの表示で、拡張度の表示を許可していた場合に
現在の拡張度をステータスに表示するように変更
段々と開発されているのが見える化します。
\ERB\キャラメイキング関連\GAPING.ER
	@PRINTFORM_GAPING_NOW,ARG
\ERB\STATUS.ERB
	804:CALL PRINTFORM_GAPING_NOW,ARG
\ERB\戦闘関連\STATUS_TRAIN.ERB
	@SHOW_STATUS_PALAM
		CALL PRINTFORM_GAPING_NOW,TARGET
