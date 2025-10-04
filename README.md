# Data collection for natural language understanding NLU tasks in the Tatar language

Аудио записи можно послушать [по ссылке в гугл диск](https://drive.google.com/drive/folders/1ZNAoliEhEgSu4WaKN8yGY2GxW4bth9DE?usp=drive_link).

**Аудиофайлы разделены по папкам, которые обозначают возраст и пол говорящего:**

`<Woman/Man>_<age>`

Распознанные тексты моделью Söyle можно посмотреть [по ссылке в гугл диск](https://drive.google.com/drive/folders/1u8EeoMah1fYDgtYevZ8KhRAmHE9OBAJs?usp=sharing). 

`soyle_results_full.txt` - файл, в котором распознаны все аудиофайлы с помощью библиотеки Söyle.

**Остальные файлы разделены по спикерам, чтобы проверить как модель распознает разные голоса. Формат файлов такой:**

`soyle_results_<w/m>_<age>.txt`

# Основные файлы

1) `en.train.conll` - обучающая выборка.
2) `final_not_full_tat.valid.conll` - валидационная выборка.
3) `tt.test_final.conll` - оригинальная тестовая выборка с адаптацией под татарскую культуру.
4) `soyle_results_full.txt` - распознанные аудиофайлы моделью Söyle
5) `tt.test_final.replaced.conll` - тестовая выборка, в которую вставили предложения, распознанные моделью Söyle.
6) `Söyle.ipynb` - код для распознавания аудиофайлов.
7) `xSID_tat.ipynb` - код для обучения модели.
8) `WER and CER.ipynb` - код для подсчета метрик CER и WER.
9) `Add_slots.ipynb` - добавление и подсчет слотов.
10) `nlu.xsid_tat.out` - файл с презсказаниями модели.

