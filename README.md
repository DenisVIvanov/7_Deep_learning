Deep_learning
Перечень заданий по работам


1. Персептрон
Реализовать обучение линейной регрессии для задачи boston house prices  с использованием torch’а  https://www.kaggle.com/vikrishnan/boston-house-prices
Реализовать нативный баесовский классификатор для MNIST (взяв всего 2 цифры “1” и “2”) сравнить с sclearn’овским


2. Многослойная нейронная сеть
Построить модель для классификации FashionMNIST. Попробуйте получить качество на тестовой выборке не ниже 88% 

3. Сверточные сети
Используя сверточные слои и архитектуру получите на fashion mnist качество не ниже 89,5%


4. Современные сверточные архитектуры
Датасет https://www.kaggle.com/ajayrana/hymenoptera-data/kernels
Обучить  модели ResNet 18 и VGG 16 с нуля (5-10 эпох)
Обучить модели ResNet 18 и VGG 16 с использованием FineTuning (5-10 эпох) и аугментации данных 

***  применить FineTuning ResNet 18 к FashionMnist. 


5. Рекуррентные сети
Обучить нейронную сеть решать шифр цезаря. Ннаписать алгоритм шифра цезаря для генерации выборки (сдвиг на К каждой буквы. Например, при сдвиге на 2 буква “А” переходит в букву “В” и тп),  Сделать и обучить сеть,  проверить качество
Применить RNN для генерации текста с выражениями героев сериала “Симпсоны”


6. RNN-2
Сгенерировать последовательности, которые бы состояли из цифр (от 0 до 9) и задавались следующим образом: x - последовательность цифр;  y1 = x1, y(i) = x(i) + x(1). Если y(i) >= 10, то y(i) = y(i) - 10, Обучить сеть предсказывать y(i) по x(i), пробовать RNN, LSTM, GRU
Применить LSTM для построения сети генерации текстов Фридриха Ницше https://s3.amazonaws.com/text-datasets/nietzsche.txt


7. RNN-3
Обучить RNN сеть seq2seq на англо-русских парах фраз https://www.manythings.org/anki/
добавить +1 рекуррентный в encoder и decoder
заменить GRU ячейки на lstm-ячейки
оценить качество во всех случаях


8. RNN Attention
Решить задачу перевода с помощью механизме внимания
обучить RNN with attention на англо-русских парах фраз seq2seq https://www.manythings.org/anki/
a. На основе скалярного произведения
b. На основе MLP


10. Computer vision
Произвести сегментацию изображений, сгенерированных по заданному алгоритму, с использованием обучения модели UNET


11. Computer Vision - Noise
Обучить LeNet на датасете MNIST,  обучить шум, который при добавлении к заданной картинке, заставит ее ошибаться в пользу другого класса


12. Работа с текстом
Обучить word2vec на фразах персонажей Симпсонов https://github.com/sujanjoejacob/Text-mining-with-Simpsons-Data
Визуаилизировать embeddings по самым частотным словам (top 1000)
Найти самые близкие слова для: homer - marge + bart bart - lisa + school marge - homer + home
построить классификатор bart/lisa с использованием полученных эмбеддингов


13. Работа с текстом  - Трансформер
Реализовать задачу машинного перевода seq2seq с использованием transformer
