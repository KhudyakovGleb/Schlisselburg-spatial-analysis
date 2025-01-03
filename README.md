# Шлиссельбург: Анализ данных и моделирование в урбанистике

Данный репозиторий создан в рамках курса **"Анализ данных и моделирование в урбанистике"**. В нем представлены ключевые реализации методов пространственного анализа данных, необходимых для оценки гипотез по преобразованию территорий.

## Описание

В репозитории представлены инструменты и методы для анализа территорий, включая получение данных, их обработку, анализ пространственных метрик и визуализацию результатов.

## Основные библиотеки
- **pandas**: обработка и анализ табличных данных.
- **osmnx**: работа с графами дорожной сети, включая получение данных с OpenStreetMap.
- **geopandas**: обработка геопространственных данных.
- **matplotlib**: визуализация данных.
- **blocksnet**: продвинутые методы анализа пространственных данных, включая доступность и центральность.
- **iduedu**: специализированные методы для получения данных о транспортной сети и границах территорий.

## Основные методы

### 1. Получение пространственных данных
- **get_drive_graph**: получение графа транспортной сети для автомобилей.
- **get_walk_graph**: создание графа пешеходной инфраструктуры.
- **get_all_public_transport_graph**: сбор данных об общественном транспорте.
- **get_boundary**: определение границ изучаемой территории.

### 2. Анализ доступности
- **AccessibilityProcessor**: инструменты для оценки доступности различных объектов и услуг на территории.
- **Accessibility**: пространственный анализ доступности ключевых объектов.

### 3. Центральность и сводные показатели
- **Centrality**: определение центральных узлов сети и ключевых путей.
- **Connectivity**: анализ связности территорий.

### 4. Прогнозирование
- **LandUsePrediction**: прогноз изменения использования земельных участков.
- **Diversity**: оценка разнообразия объектов на территории.

### 5. Обеспеченность
- **Provision** и **ProvisionMethod**: анализ плотности объектов, таких как школы, больницы и магазины, и их обеспеченности.

### 6. Визуализация
- Построение картографических визуализаций с использованием **matplotlib** и **geopandas**.

## Структура репозитория
- **Jupyter Notebook**: основной файл с кодом для выполнения анализа.
- **Данные**: входные данные, включая географические границы и графы сетей (при наличии).
- **README**: описание репозитория и методов.

## Использование
1. Установите зависимости из `requirements.txt`.
2. Откройте Jupyter Notebook для выполнения анализа.
3. Следуйте инструкциям в ноутбуке для запуска анализа вашей территории.

## Авторы и вклад
- Глазов Юрий
- Грук Николай
- Худяков Глеб
- Чичков Егор

## Лицензия
Данный проект распространяется под свободной лицензией. Используйте материалы в образовательных и исследовательских целях.
