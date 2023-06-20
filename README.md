# finkit

I. Верстка

Сделать верстку небольшого блока:
https://www.figma.com/file/3RGIortwq95cfZReQ3diyp/Fin-Kit-Test

Не делал Pixel Perfect, т.к. этого не было в требованиях, плюс в макете есть некоторые неточности.
Размеры и расположение некоторых элементов немного изменены по сравнению с макетом, т.к. на макете левый и правый отступы гораздо больше,
чем указанные в требованиях, поэтому относительные размеры соблюдать нецелесообразно.
Но в целом, все, что было на макете, реализовано, вплоть до мелких деталей.
Кроме адаптивных размеров блоков сделал еще адаптивный размер текста и некоторых элементов, например изображения руки с телефоном 
(согласно макетам Mobile и Desktop).

На всякий случай дублирую сюда требования:

Требования (обязательные):
- верстка на чистом HTML/CSS (без фреймворков, библиотек, систем сборки и т.д.)
- максимальная ширина 1100px с padding-полями 60px с каждой стороны (при большем разрешении выравнивание по центру)
- адаптивная верстка под мобильные устройства (телефон и планшет, также все должно корректно отображаться на переходных разрешениях)
- изображения должны быть оптимизированы, но поддерживать качество retina-экранов
- все иконки подключаются через web-шрифты (можно сделать через сервис fontello)
- именование изображений, классов и прочих css-элементов идет через snake_case
- простой и понятный код
