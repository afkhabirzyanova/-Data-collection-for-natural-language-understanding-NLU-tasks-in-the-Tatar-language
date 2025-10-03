# Data collection for natural language understanding NLU tasks in the Tatar language

Аудио записи можно послушать [по ссылке в гугл диск](https://drive.google.com/drive/folders/1ZNAoliEhEgSu4WaKN8yGY2GxW4bth9DE?usp=drive_link).

Аудиофайлы разделены по папкам, которые обозначают возраст и пол говорящего:

`<Woman/Man>_<age>`

Распознанные тексты моделью Söyle можно посмотреть [по ссылке в гугл диск](https://drive.google.com/drive/folders/1u8EeoMah1fYDgtYevZ8KhRAmHE9OBAJs?usp=sharing). В названии файла тоже есть обозначения (пол и возраст).

`soyle_results_full.txt` - файл, в котором распознаны все аудиофайлы с помощью библиотеки Söyle.

Остальные файлы разделены по спикерам, чтобы проверить как модельраспознает разные голоса. Формат файлов такой:

`soyle_results_<w/m>_<age>.txt`

# Основные файлы

1) `en.train.conll` - обучающая выборка.
2) `final_not_full_tat.valid.conll` - валидационная выборка.
3) `tt.test_final.replaced.conll` - тестовая выборка. В нее вставлены предложения, которые распознала модель Söyle.
4) `tt.test_final.conll` - разметка с адаптацией под татарскую культуру.

# Коды, которые исправляют форматы файлов
