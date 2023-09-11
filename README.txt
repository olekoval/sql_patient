
(main_download.ipynb - не работает при
AND principal_diagnosis LIKE ANY ('{I60.%, I61.%, I62.%, I63.%}')

1. При необходимости обновить справочники.
    Для єтого запустить dictionary_download.ipynb

2. В pgAdmin запустить main_dounloads.sql.
    Файл сохранить как ./data/main.csv
ИЛИ 
    запустить main_download.ipynb
    Файл сохранить как ./data/main.csv

3. Обработать main.csv запустив 
 EDA.ipynb
