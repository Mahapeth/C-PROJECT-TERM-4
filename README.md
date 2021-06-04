# Модуль "Решение СЛАУ методом простых итераций" для Python

<img src="https://img.shields.io/badge/Python-3.8-9cf" width="100" alt="Python 3.8">  <img src="https://img.shields.io/badge/Version-0.0.1-9cf" width="120" alt="Version 0.0.1">

<h3> <i> 🐍 Проект по предмету "Языки и методы программирования" выполнили обучающиеся 2 курса на направлении прикладная математика и информатика: 🐍 </i> </h3>

<a href='https://github.com/Mahapeth'> <b> <i> Петухова Мария (ПМ-1901) </i> </b> </a>, <a href='https://github.com/YumanovS'> <b> <i> Юманов Сергей (ПМ-1902) </i> </b> </a>
<h2> <i> Актуальность: </i> </h2>
Системы линейных алгебраических уравнений (СЛАУ) появляется почти в каждой области прикладной математики. Решение СЛАУ является одной из самых распространенных и важных задач вычислительной математики. Актуальность темы нашего проекта определяется тем, что алгоритмы решения СЛАУ итерационными методами обычно более сложные по сравнению с прямыми методами. Соответственно объем вычислений заранее определить трудно, так как он зависит от степени близости начального приближения к «точному» значению. Поэтому разработанный нами модуль будет упрощать решение СЛАУ итерационным методом.
<h2> <i> Цель: </i> </h2>
Создать модуль "Решение СЛАУ методом простых итераций (последовательных приближений)" на языке программирования С, адаптированный под язык программирования Python.
<h2> <i> Задачи: </i> </h2>

1. Определить необходимую теоретическую основу и изучить ее.
2. Реализовать программу "Решение СЛАУ методом простых итераций" на языке программирования С.
3. Скомпилировать Python модуль.

<h2> <i> Процесс разработки: </i> </h2>
Изначально каждый участник команды работает в своей ветке. После того, как программа будет написана, будет сделан PullRequest (соединение частей проекта).

<h2> <i> Как использовать модуль? </i> </h2>
Скачиваем все файлы и пишем в консоли последовательно:

python setup.py build

python setup.py install

python

import slausolve

slausolve.solve(1,0.17,-0.25,0.54,0.47,1,0.67,-0.32,-0.11,0.35,1,-0.74,0.55,0.43,0.36,1,0.3,0.5,0.7,0.9)
