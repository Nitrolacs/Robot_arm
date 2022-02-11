# Robot-arm
Робот с машинным зрением на основе ROS 🤖
## Описание проблемы

В настоящее время многим людям приходится ежедневно выполнять обилие монотонной механической работы на складах и фабриках. Но благодаря робототехнике появляется возможность автоматизировать подобные задачи и освободить время людей. Также, как показывает практика, использование роботизации позволяет справляться быстрее с поставленными задачами и удешевить производство.
______
Данный проект, выполненный в рамках дисциплины ВВПД, посвящён созданию продвинутой симуляции интеллектуального робота. Поддержка машинного зрения позволит роботу работать автономно, без стороннего управления оператором. Он сможет выполнять сортировку различных объектов а также осуществлять свободные перемещения в пределах ограниченного пространства.  
В рамках проекта планируется создание компьютерной модели робота и симуляции выполняемых им задач с использованием фреймворка [ROS](https://www.ros.org/) и симулятора [Gazebo](https://www.gazebosim.org/).
______
**Роботы-манипуляторы** — это один из типов промышленных роботов. Они способны выполнять те же функции, что и человеческая рука: брать предметы, перемещать их в пространстве, осуществлять работу с помощью специальных инструментов. Соединения сегментов манипулятора допускают как вращательные, так и поступательные движения. 

![Robot-arm](https://cdn.discordapp.com/attachments/940448001250447411/940449205791625256/oZYd_WJencs.png)
## Функционал

Планируемый робот должен поддерживать следующие функции: 
- вращение корпуса с несколькими степенями свободы;
- ведение видеосъёмки, обнаружение предметов заданного цвета с помощью машинного зрения;
- перемещение в точку с известными координатами;
- захват и перемещение предметов.

**Задачи**:
- [ ]  Найти подходящую URDF модель робота
- [ ]  Адаптировать модель для запуска в Gazebo
- [ ]  Создать в Gazebo сцену с окружением для робота
- [ ]  Написать python скрипт для управления роботом по команде пользователя
- [ ]  Добавить возможность перемещения манипулятора в произвольно заданную точку (используя movit)
- [ ]  Добавить роботу поддержку камеры
- [ ]  Обрабатывать видео с камеры с помощью машинного обучения
- [ ]  Обеспечить возможность захвата распознаваемых предметов

![Robot-computer-vision](https://user-images.githubusercontent.com/69214030/152913378-1f5780fe-e10e-46cf-9cd9-a225bafca931.png)
