# DDI
Drug-Drug Interactions


## Pubmed_last.ipynb
Запросы в пабмед

## gs_final_general.ipynb
Запросы в GoogleScholar

## Res.ipynb 
Обработка данных

## cor_clean_all_v1.csv
Таблица с итоговыми данными
### Столбцы:
drug - название лекарства

CYPххх_l - литературные данные по взаимодействию каждого лекарства с цитохромами

cytochrome - количество ответов на запрос drug name+substrate+cytochrome

CYPxxx - количество ответов на запрос drug name+substrate+CYPxxx

year - год первой статьи по запросу лекарства в PubMed

count_pubmed - количество ответов на запрос drug name+substrate+cytochrome в PubMed

count_name - количество ответов на запрос drug name в PubMed

Все остальное -- нормировки, которые можно отследить по коду из *Res.ipynb*
