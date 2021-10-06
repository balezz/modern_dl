# Modern deep learning course. Современные нейросетевые технологии.   

Based on dlcourse.ai and Stanford CS230n, CS231n.

Assignment results see @ RESULTS.csv

Экзамен будет проходить в письменном виде, у вас будет 90 минут на оформление РУКОПИСНОГО ответа. Оценки будут выставлены в течение трех суток. При необходимости индивидуальной беседы будет назначен созвон с видеозаписью.
Билет будет включать в себя три вопроса: по основам DL, по фреймворку Keras и практическое задание в Google Colab.

Вопросы по основам нейросетевых технологий:  

- Линейное отображение. Векторно-матричное дифференцирование.
- Градиент функции многих переменных. Физический смысл. Методы вычисления.
- Классификация. Метод опорных векторов.
- Метрики качества классификации.
- Кросс-валидация. Выборки train, validation, test.
- Процесс обучения классификатора. Функции потерь.
- Преобразование Softmax и функция потерь Cross Entropy loss.
- Механизм обратного распространения ошибки (backpropagation).
- Стохастический градиентный спуск. Батчи обучающей выборки.
- Продвинутая оптимизация. Momentum SGD.
- Гиперпараметры. Скорость обучения и размер батча.
- Переобучение модели и регуляризация.
- Многослойные сети. Вычислительный граф.

Вопросы по Keras:
Основной ресурс для подготовки https://keras.io/api/  

- Фреймворк Keras. Назначение. Основные модули.
- Способы создания моделей. Sequential and Model subclassing, Functional API.  
- Model training APIs
- Model saving & serialization APIs
- Layer class. Activations.
- Layer class. Weight initializers, regularizers.
- Convolution layers. Separable, Depthwise, Transpose.
- Pooling layers. Max, Average, Global.
- Preprocessing layers. Text, Numerical, Categorical.
- Normalization layers.
- Regularization layers.
- Callbacks API.
- Data preprocessing. Image, Text, TimeSeries.
- Optimizers.
- Metrics.
- Losses.
- Keras Applications.

Практические задания:  
Создайте модель заданной архитектуры и обучите на встроенном датасете tf.keras.datasets.cifar10.load_data().  
Гиперпараметры подберите самостоятельно:  
- Dense - Dense - Dense, Model subclassing.
- Conv - Dense - Dense, Model subclassing.
- Conv - Conv - Dense, Model subclassing.
- Dense - Dense - Dense, Sequential subclassing.
- Conv - Dense - Dense, Sequential subclassing.
- Conv - Conv - Dense, Sequential subclassing.
- Dense - Dense - Dense, Functional API.
- Conv - Dense - Dense, Functional API.
- Conv - Conv - Dense, Functional API.
