# Данные и скачивание

Проект использует открытые объектные (табличные) спутниковые продукты по факельному сжиганию газа (VIIRS Nightfire / flare site surveys).

## Что нужно скачать
Скачайте годовые файлы формата CSV:
- eog_global_flare_survey_2012_flare_list.csv
- ...
- eog_global_flare_survey_2019_flare_list.csv
а также при необходимости:
- eog_global_flare_survey_2012_country_summary.csv
- ...
- eog_global_flare_survey_2019_country_summary.csv

## Куда положить в Colab
В Colab создайте папку:
`/content/data/raw/`

И загрузите туда все CSV.

Пример структуры:
`/content/data/raw/eog_global_flare_survey_2012_flare_list.csv`

## Демо-режим
Для быстрого запуска без скачивания полных данных используется:
`data/sample_data/`
Это небольшой фрагмент, достаточный для демонстрации пайплайна.
