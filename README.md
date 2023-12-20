# PI_3
Practical assignment for the third module of the discipline "Software Engineering" UrFU     

## TranslaterML(API)

### Launching the application

To run the application, you need to install the dependencies and run the streamlet:
 - Installing dependencies
```bash
pip install -r requirements.txt
```
 - run the application
```bash
uvicorn  app:app
(for Windows: python -m uvicorn  app:app)
```
#### The following ready-made models were used:
Helsinki-NLP/opus-mt-en-ru     
Helsinki-NLP/Opus-mt-ru-en

@InProceedings{TiedemannThottingal:EAMT2020,
  author = {J{\"o}rg Tiedemann and Santhosh Thottingal},
  title = {{OPUS-MT} — {B}uilding open translation services for the {W}orld},
  booktitle = {Proceedings of the 22nd Annual Conferenec of the European Association for Machine Translation (EAMT)},
  year = {2020},
  address = {Lisbon, Portugal}

# PI_3
Практическое задание по пятому модулю дисциплины "Программная инженерия" УрФУ

### Запуск приложения

Чтобы запустить приложение, вам необходимо установить зависимости и запустить streamlet:

 - Установка зависимостей
```bash
pip install -r requirements.txt
```
 - Запуск приложения
```bash
uvicorn  app:app
(for Windows: python -m uvicorn  app:app)
```

### Были использованы следующие готовые модели:
Helsinki-NLP/opus-mt-en-ru    
Helsinki-NLP/Opus-mt-ru-en
