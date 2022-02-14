<p align="center">
  <br>
  <img alt="Logo" src="media/robotic-arm.png" width = 250px>
  <br><br>
</p>

<div align="center">

![GitHub](https://img.shields.io/github/license/nitrolacs/Robot_arm?color=blue&style=for-the-badge)

</div>

<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</div>

# [![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Robot+arm)](https://git.io/typing-svg)

<img align="right" width="400" alt="Robot_arm_working" src = "media/Robot_arm_working.gif">

Робот с машинным зрением на основе ROS 🤖  


## [![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Описание+проблемы)](https://git.io/typing-svg)

В настоящее время многим людям приходится ежедневно выполнять обилие монотонной механической работы на складах и фабриках. Но благодаря робототехнике появляется возможность автоматизировать подобные задачи и освободить время людей. Также, как показывает практика, использование роботизации позволяет справляться быстрее с поставленными задачами и удешевить производство.
______
Данный проект, выполненный в рамках дисциплины ВВПД, посвящён созданию продвинутой симуляции интеллектуального робота. Поддержка машинного зрения позволит роботу работать автономно, без стороннего управления оператором. Он сможет выполнять сортировку различных объектов а также осуществлять свободные перемещения в пределах ограниченного пространства.  
В рамках проекта планируется создание компьютерной модели робота и симуляции выполняемых им задач с использованием фреймворка [ROS](https://www.ros.org/) и симулятора [Gazebo](https://www.gazebosim.org/).
______
**Роботы-манипуляторы** — это один из типов промышленных роботов. Они способны выполнять те же функции, что и человеческая рука: брать предметы, перемещать их в пространстве, осуществлять работу с помощью специальных инструментов. Соединения сегментов манипулятора допускают как вращательные, так и поступательные движения. 

<img width="500" alt="Robot_arm_1" src = "media/Robot_arm_2.png">

## [![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Функционал)](https://git.io/typing-svg)

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

<img width="500" alt="Robot_arm_2" src = "media/Robot_arm_1.png">
