---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
subtitle: Первоначальна настройка git 
author:
  - Седохин Д.А.  
institute:
  - Российский университет дружбы народов, Москва, Россия  
  - 25 февраля 2024
 

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
##Fonts 
mainfont: PT Serif 
romanfont: PT Serif 
sansfont: PT Sans 
monofont: PT Mono 
mainfontoptions: Ligatures=TeX 
romanfontoptions: Ligatures=TeX 
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase 
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Седохин Даниил Алексееивч
  * Группа НПИбд-02-23
  * Российский университет дружбы народов
  * <https://github.com/Daniil2234>

:::
::: {.column width="30%"}

:::
::::::::::::::

# Вводная часть

## Объект и предмет исследования

- Система контроля версий GIT

## Цель работы

- Изучить идеологию и применение средств контроля версий.  
 - Освоить умения по работе с git.


## Установка git 
- Установка git

![](image/1.jpg){width=50%}

## Установка gh
- Установка gh

![](image/2.jpg){width=50%}

## Базовая настройка git
- Задаём имя и email владельца  
- Настройка utf-8

![](image/3.jpg){width=60%}

![](image/30.jpg){width=60%}

## Создание ключей ssh
- Алгоритм rsa 

![](image/6.jpg){width=60%}

## Создание ключей ssh
- Алгоритм ed25519

![](image/7.jpg){width=60%}

## Создание ключей pgp
- Генерация ключа  
- Указываем тип, размер, срок действия, имя, адрес..

![](image/8.jpg){width=60%}

## Добавление PGP ключа в GitHub
- Копируем отпечаток приватного ключа  
- Копируем свой ключ PGP 

![](image/10.jpg){width=60%}

## New GPG key
- В GitHub вставляем полученный ключ

![](image/11.jpg){width=60%}

## Настройка автоматических подписей коммитов git
- Настройка подписей коммитов  

![](image/12.jpg){width=60%}

## Настройка gh
- Авторизация через браузер

![](image/13.jpg){width=60%}

## Создание репозитория курса на основе шаблона
- Создаём репозиторий курса

![](image/14.jpg){width=60%}

##  Настройка каталога курса
- Удаляем лишние файлы  
- Создаём необходимые каталоги

![](image/16.jpg){width=60%}

##  Отправка файлов на сервер

![](image/17.jpg){width=60%}

## Вывод
- Я Изучил идеологию и применение средств контроля версий.  
    Освоил умения по работе с git.
