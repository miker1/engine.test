���������� ������ ���� ���������
https://github.com/2amigos/yii2-ckeditor-widget
����������:
use dosamigos\ckeditor\CKEditor;
<?= $form->field($model, 'text')->widget(CKEditor::className(), [
        'options' => ['rows' => 6],
        'preset' => 'basic'
    ]) ?>