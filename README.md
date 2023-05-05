# Глубокое обучение в анализе гиперспектральных изображений - сегментация пожаров
## Описание репозитория
Перед запуском проекта установите неоходимые зависимости из файла requernmants.txt
```bash
pip install -r requirements.txt
```
### Примеры использования
Корневая директория сожержит примеры использования разработанного функционала.  
*segmentation.py* - пример сегментации изображения, полученного со спутникого снимка
### Модели глубокого обучения
Директория *train* содержит файлы программы, связанные с обучением моделей. 
Файлы обученных моделей можно скачать через google drive по [ссылке](https://drive.google.com/drive/folders/1QcJIFJjenfI00Y8Z7DHgiJ03xUzYY7kA?usp=sharing). После скачивания поместите файлы моделей в директорию *models*. 
### Вспомогательные файлы
Директория *utils* содержит файлы, реализующие логику получения спутникого изображения, его обработки и вывода.
