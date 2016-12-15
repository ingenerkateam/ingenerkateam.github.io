![](https://avatars1.githubusercontent.com/u/24490920?v=3&s=200)

# Инженерка

[TOC]
--

## Наши проекты
* [lazers](https://github.com/ingenerkateam/lazers) - [NeverMine17](https://github.com/NeverMine17) - [![Build status](https://ci.appveyor.com/api/projects/status/ar6q91juwfla7gwk)](https://ci.appveyor.com/project/NeverMine1732586/lazers) 

* [Car](https://github.com/ingenerkateam/Car) -  [SvyatkinYura](https://github.com/SvyatkinYura) - [![Build status](https://ci.appveyor.com/api/projects/status/1cxoaycor4aaye57)](https://ci.appveyor.com/project/NeverMine1732586/car)

* [space-ship](https://github.com/ingenerkateam/space-ship) - [qwinner](https://github.com/quwinner) - [![Build status](https://ci.appveyor.com/api/projects/status/p04y6xr5ysa39ycg)](https://ci.appveyor.com/project/NeverMine1732586/space-ship)

* [Bottles](https://github.com/ingenerkateam/Bottles) - [sosiska2281337](https://github.com/sosiska2281337) - [![Build status](https://ci.appveyor.com/api/projects/status/5uocts4kky386adr)](https://ci.appveyor.com/project/NeverMine1732586/bottles)
  
  и другие...

----

## Как встроить AppVeyor

### Инструкция
1. Скачайте [Visual Studio](https://www.visualstudio.com/ru/downloads/)
2. Создайте новый проект.
3. Добавите все исходники в проект.
4. Сохраните проект.
5. Измените строку ClInclude оставив только название.
6. Отправите *.vsxproj в GitHub
_Все!_

----

### Зачем нужен Visual Studio 

Дело в том что AppVeyor использует утилиту msbuild,
о которой можно узнать в [Wiki](https://ru.wikipedia.org/wiki/MSBuild).
Эта утилита требует проекта VS для сборки.

#### Зачем нужен 5 шаг в инструкции?
T.к проекты VS хранятся в совершенно другой папке а ваши исходники в другом, VS нужно указивать полный путь до исходников.
