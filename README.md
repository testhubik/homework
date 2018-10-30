# Домашнее задание

В этом задании надо сделать страницу видеонаблюдения.

На странице можно смотреть HLS видеопотоки с веб-камер, переключать камеры,
накладывать риал-таймовые фильтры на видео и следить за активностью в умном доме.

Для разработки вы можете использовать тестовые видео-потоки
(о том, как их развернуть, можно почитать [тут](streams/README.md)).

Страница "Видеонаблюдение" должна работать в актуальной версии Chrome на десктопе и
на Android

## Пункты, которые нужно реализовать

1. **Страница-вкладка в интерфейсе умного дома "Видеонаблюдение"**:
    1. Клик по превью видео разворачивает соответствующее видео на всю страницу.
    
    2. Анимацию разворачивания видео можно сделать по своему усмотрению
    
    3. Когда видео раскрыто на всю страницу, в интерфейсе нужно предусмотреть кнопку
    "Все камеры", которая позволяет вернуться назад.
    
    4. Анимация переключения видео должна работать без тормозов (без просадки FPS на странице)

    5. Видео-поток с камеры может быть плохого качества (размытый, засвеченный или затемненный) - добавить на экран просмотра видео
    возможность регулировать его яркость и контрастность. Для контролов настройки яркости/контрастности можно использовать `input`.

    6. Реализовать анализатор громкости звука в потоке из открытой камеры (в виде столбчатой диаграммы).

## Бонусные задания

1. Добавить информацию об уровне освещенности в комнате.
2. Реализовать детектор движения в видео (нарисовать поверх видео прямоугольник, где происходит движение).

Работа анализаторов не должна давать серьезных просадок FPS.
