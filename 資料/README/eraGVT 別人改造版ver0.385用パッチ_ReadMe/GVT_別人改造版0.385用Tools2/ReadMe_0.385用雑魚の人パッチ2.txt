�y���Ӂz
�ύX�_����������Tool1�́u�X�����O�v�t�H���_����ɂ��Ă���A�㏑����������

�ėp�֐�@PRINT_RGBTEXT(ARGS:0,ARGS:1)���쐬
ARGS:0�ɐF�AARGS:2��PRINTFORM�p�̕�������w��
�w�肵�������ɐF�t�����ĕϊ�����

@COLOR_T_SHAPE(ARGS:0,ARGS:1)
�ėp�֐�@PRINT_RGBTEXT(ARGS:0,ARGS:1)�𗘗p���ĐG��̐F��\������֐�

@T_STATUS_BCOLOR
�G��X�e�[�^�X���ԂŐF���ǂ����邩�Ԃ��֐�

�y�ύX�_�z

�w�E�̂������t�F���`�I�̍s���w��̕����̏C��

SLANG������p�ƒn�̕��l�ɕ���
%SPOKENSLANG("����")%	:����ł̖��̂��ȒP�ɕԂ����߂̃V���[�g�J�b�g
	@CALLSLANG�i���ʁj���A@WRITTENSLANG�i���ʁj�ɕύX
	�n�̕��̕���iWRITTEN�j�ƁA����̌���iSPOKEN�j�Ŏ��o�I�ɂ킩��悤

%SLANG_N(TARGET)%	;�n�̕��̓���
	����Ȃ̂ɒ��Ƀ}�E�X��M�����ď��������Y��Ă����̂ŏC��

%SLANG_Labia(TARGET)%	;�n�̕��̉A�O
	���̊ȗ����s���ƃG���[���N����̂ŁA�C��


�퓬���Ƀp�����[�^�̕\���ŁA�g���x�̕\���������Ă����ꍇ��
���݂̊g���x���X�e�[�^�X�ɕ\������悤�ɕύX
�i�X�ƊJ������Ă���̂������鉻���܂��B
\ERB\�L�������C�L���O�֘A\GAPING.ER
	@PRINTFORM_GAPING_NOW,ARG
\ERB\STATUS.ERB
	804:CALL PRINTFORM_GAPING_NOW,ARG
\ERB\�퓬�֘A\STATUS_TRAIN.ERB
	@SHOW_STATUS_PALAM
		CALL PRINTFORM_GAPING_NOW,TARGET
