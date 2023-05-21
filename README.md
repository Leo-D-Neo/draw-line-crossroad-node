# draw-line-crossroad-node

## Запуск
- Создание образа: dts devel build -f
- Запуск контейнера: dts devel run

## Тестирование 
После запуска контейнера начнется обмен сообщениями(image) , чтобы просмотреть содержимое топика нужно открыть другую консоль в корне проэкта и ввести следующие команды:
- dts start_gui_tools
- rosrun image_view image_view image:=/image

## План разработки

