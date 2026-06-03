# Data collection for natural language understanding NLU tasks in the Tatar language

Аудио записи `/data/audio`. Аудиофайлы разделены по папкам, которые обозначают возраст и пол говорящего: `<Woman/Man>_<age>`.

Датасеты `/data/text`.

Коды `/data/scripts`.



# Основные файлы

`soyle_results_full.txt` - распознанные аудиофайлы моделью Söyle, `soyle_results_<w/m>_<age>.txt`
`söyle.py` - код для распознавания аудиофайлов.
`machamp.ipynb` - код для обучения модели.
`wer_and_cer.py` - код для подсчета метрик CER и WER.
`add_#slots.ipynb` - добавление и подсчет слотов.
`entities.py` - списи сущностей для каждого вида.
`train_adopted.ipynb` - код для замены сущностей.

