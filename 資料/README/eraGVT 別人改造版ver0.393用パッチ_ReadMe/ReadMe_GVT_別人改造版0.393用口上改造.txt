�v���g�^�C�v�Ȃ̂ŁA�v�e�X�g�ł�

�yVer0.393�p�z
CFLAG:2 > 0�ł͂Ȃ��ACFLAG:1 > 0�ł���
�قƂ�Ǐ��������ł�

\ERB\����
;�ϐg�O�̂�����
@KOJO_0_BATTLE_CHARA_TRANSFORMCALL
CALL TRANSFORM, 1
TRYCALL KOJO_0_COLOR
;�ϐg���������ݒ�
IF CFLAG:(TARGET):4 == 1
	PRINTFORML �u%CSTR:TARGET:2%�v
ELSE
	SELECTCASE RAND:10
		CASE 1
			PRINTFORML �u�`�F���W�v
		CASEELSE
			PRINTFORML �u�ϐg�v
	ENDSELECT
ENDIF


\ERB\�R�}���h��\COMF0.ERB
;�ϐg
SIF CFLAG:1 < 1
	CALL TRANSFORM, 1



�ɕύX�A����肪�����Ă����s�œK�������悤�ɂȂ�܂����B
�s�N�V�B�~�T���A�Ăяo��������p�ɐU�蕪�����܂����B



�yVer0.392�p�z
;�G�L�����ɏ���
@KOJO_0__BATTLE_END_WIN_ENEMY
@KOJO_0_BATTLE_END_WIN_ENEMY

_������ł����̂ŏ����܂���



���i��^�ς���e���v���[�g�ƃe�X�g
500�ԂɓV��������i�s�N�V�B�~�T�j��ݒ�
COLOR�ݒ�̂Ƃ���ŁA�ϐg���Đ��i�̐ݒ�ŕύX����悤�ɂ���
�Ăяo���͔̂ėp�Ȃ̂ŁA����Ȃ��Ƃ��������