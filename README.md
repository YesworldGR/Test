# Начало работы

## Запускаем первую ячейку для получения предсказаний от модели 

![image](https://github.com/user-attachments/assets/bf93e757-57ec-4166-83a0-1b2943aec32c)

Далее выбираем изображения для которых мы хотим посчитать метрику и переносим их в отдельную папку.

## Запускаем вторую ячейку 

![image](https://github.com/user-attachments/assets/330d28f2-7ead-4776-aa34-1a48309de94a)

Где photos_path - путь к папке с выбранными изображениями
source_labels_val - путь к папке, где хранилась разметка датасета
source_labels_predict - путь к папке, где хранится разметка предсказаний
destination_gt - папка, в которыю код скопирует разметку для выбранных картинок
destination_pr - папка, в которую код скопирует разметку с предсказаниями для выбранных картинок

## Запуск третий ячейки 

![image](https://github.com/user-attachments/assets/f6eeb5ba-bb79-4da9-91e2-b14c775b0247)

Этот код перевёдет разметку YOLO в более привычный формат координат 

## Запускаем расчёт метрик 

![image](https://github.com/user-attachments/assets/2de5040b-6c06-473a-89d4-77aa9481d1da)

# Комментраий
Остальные ячейки кода, которые не представлены на скриншотах опциональные и можно ими не пользоваться
