# **Программное средство реализации онлайн-ресурса для формирования базы вакансий в IT-сфере**

Приложение для поиска работы и сотрудников в IT сфере.

Ссылки на репозитории сервера и клиента:
## Клиент
https://github.com/artemij-petrovskij/PetrovskyAI_214371_RIOPK_Client

## Сервер
https://github.com/artemij-petrovskij/PetrovskyAI_214371_RIOPK_Server

## **Содержание**

1. [Архитектура](#Архитектура)
	1. [C4-модель](#C4-модель)
	2. [Схема данных](#Схема_данных)
2. [Функциональные возможности](#Функциональные_возможности)
	1. [Диаграмма вариантов использования](#Диаграмма_вариантов_использования)
	2. [User-flow диаграммы](#User-flow_диаграммы)
3. [Детали реализации](#Детали_реализации)
	1. [UML-диаграммы](#UML-диаграммы)
	2. [Спецификация API](#Спецификация_API)
	3. [Безопасность](#Безопасность)
	4. [Оценка качества кода](#Оценка_качества_кода)
4. [Тестирование](#Тестирование)
	1. [Unit-тесты](#Unit-тесты)
	2. [Интеграционные тесты](#Интеграционные_тесты)
5. [Установка и  запуск](#installation)
	1. [Манифесты для сборки docker образов](#Манифесты_для_сборки_docker_образов)
	2. [Манифесты для развертывания k8s кластера](#Манифесты_для_развертывания_k8s_кластера)
6. [Лицензия](#Лицензия)
7. [Контакты](#Контакты)

---
## **Архитектура**

### C4-модель

Иллюстрация и описание архитектуры ПС
Архитектура ПС (общий вид):
![Архитектура](/images/arc2.png)

Более подробная архитектура:
![Архитектура](/images/arc.png)
---
Первый уровень показывает как система взаимодействует с внешними сущностями (пользователями, внешними системами).
![с4 1 диаграмма](/images/c4-1.png)
---
Второй уровень показывает какие контейнеры существуют в системе и как они взаимодействуют друг с другом.
![с4 2 диаграмма](/images/c4-2.png)
---
Уровень компонентов в нотации моделирования архитектуры C4 предоставляет более подробное представление структуры системы. 
![с4 3 диаграмма](/images/c4-3.png)
---
Четвертый уровень показывает организацию кода основных частей программного средства, на примере интерфейса IResume с последующей реализацией.
![с4 4 диаграмма](/images/c4-4.png)

### Схема данных

Описание отношений и структур данных, используемых в ПС. Также представить скрипт (программный код), который необходим для генерации БД

---

## **Функциональные возможности**

### Диаграмма вариантов использования

![Use Case диаграмма](/images/use-case.png)
Сервис позволяет получать роль соискателя или кандадата.

### User-flow диаграммы
User-flow диаграмма для пользователя в роли соискателя.
![Use Case диаграмма](/images/user-flow-1.png)

Описание переходов между части ПС для всех ролей из диаграммы ВИ (название ролей должны совпадать с тем, что указано на c4-модели и диаграмме вариантов использования)


---

## **Детали реализации**

### UML-диаграммы


![Use Case диаграмма](/images/use-case.png)

### Спецификация API

Представить описание реализованных функциональных возможностей ПС с использованием Open API (можно представить либо полный файл спецификации, либо ссылку на него)

### Безопасность

Описать подходы, использованные для обеспечения безопасности, включая описание процессов аутентификации и авторизации с примерами кода из репозитория сервера

### Оценка качества кода

Используя показатели качества и метрики кода, оценить его качество

---

## **Тестирование**

### Unit-тесты

Представить код тестов для пяти методов и его пояснение

### Интеграционные тесты

Представить код тестов и его пояснение

---

## **Установка и  запуск**

### Манифесты для сборки docker образов

Представить весь код манифестов или ссылки на файлы с ними (при необходимости снабдить комментариями)

### Манифесты для развертывания k8s кластера

Представить весь код манифестов или ссылки на файлы с ними (при необходимости снабдить комментариями)

---

## **Лицензия**

Этот проект лицензирован по лицензии Mozilla Public License 2.0 - подробности представлены в файле [[License.md|LICENSE.md]]

---

## **Контакты**

Автор: petrovsky.artem.dev@gmail.com