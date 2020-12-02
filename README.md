# Распознавание образов

**Цель:** исследование методов и алгоритмов для распознавания лиц и идентификации.

**Тема проекта по распознаванию образов:**  «Распознавание лица человека с идентификацией».

**Описание задачи:** необходимо разработать рабочий проект (систему, приложение) по распознаванию человеческих лиц с идентификацией человека (например, его имя). Система должна распознавать не менее 15 лиц. На вход системе будет подаваться видеопоток в реальном времени. На выходе – распознанное и идентифицированное лицо.

**Методы:** для распознавания были взяты три метода

  - Haar cascades (из библиотеки OpenCV),
  - HOG (библиотека Face recognition),
  - MTCNN (библиотека MTCNN).
  
**Выводы:** таким образом нами были рассмотрены три способа распознавания и идентификации лиц в видеопотоке. В целом, результаты оказались положительными. Все алгоритмы распознали и идентифицировали человека.

**Плюсы и минусы**

Результаты показали, что самым устойчивым алгоритмом оказался HOG (Histograms of oriented gradients) из библиотеки Face Recognition. Данный метод не требует настройки гиперпараметров и хорошо работает «из коробки».

Каскады Хаара и MTCNN требуют настройки параметров и занимают более долгий процесс обучения. Несмотря на это MTCNN имеет больший потенциал, чем остальные алгоритмы, и при правильном тюнинге модели может показать лучший результат. Также MTCNN определяет не только лицо, но и определяет координаты глаз, носа и кончиков рта.

