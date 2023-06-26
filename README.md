 # Командный проект группы №1 (25-3F01032023)
## Git flow
## Первоначальная настройка проекта
* ``` git clone git@github.com:Abubakir111/Geeks-team-project.git ``` Копируем проект
*  ``` npm install ``` Устанавливаем зависимости
## Рабочий цикл
* ``` git checkout main ``` Если мы не в главной ветке, переходим в нее
* ``` git pull origin ``` Синхронизируем главную ветку с удаленным репозиторием (Гитхаб)
* ``` git checkout -b <branch-name> ``` Создаем рабочую ветку для нового функционала. НЕ вносим изменения в ветку main вообще
*  Вносим изменения в рабочей ветке, по обычному, делаем коммиты при достижении промежуточных результатов. Достигнув результата и проверив работоспособность нового функционала, делаем коммит
* ``` git add . && git commit -m '<commit-message>' ``` Команда ``` git add . ``` (с точкой) включает в будущий коммит все измененные и созданные файлы; && выполняет команды последовательно
* ``` git push -u origin HEAD ```И загружаем его на Гитхаб. Флаг ``` -u ``` (сокращение от``` --set-upstream```) нужен для создания на гитхабе новой ветки, соответствующей нашей рабочей ветке. Когда ветка на Гитхабе создана, мы можем загружать в нее корректировки краткой командой ``` git push ```(не забывая перед этим сохранить файлы и сделать коммит)
* На странице репозитория создаем ```Pull request ``` и ожидаем одобрения наших изменений другими соавторами. Соавторы могут оставлять комментарии к изменениям с вопросами, предложениями и замечаниями. После одобрения происходит слияние ( ```merge ```) новой ветки с главной веткой проекта ( ``main ``). Создание пул-реквеста не мешает нам продолжать работу и вносить изменения в рабочую ветку и загружать ее на сервер заново. Также возможно создание новой локальной рабочей ветки для работы над следующей задачей
* После слияния возвращаемся в локальную ветку main и синхронизируем ее с последними изменениями на сервере ``` git checkout main && git pull```
* Бинго! Дело сделано


‼️‼️‼️‼️‼️

```Проект 1```

Tasks:
 1. Разбить на компоненты и назвать их +
 2. Разделить задачи +
 3. Разобраться с гитом
 4. Выбрать тимлида + (Бакир)

```Бакир```
1. header
2. logo
3. logoCards

```Мухамед```
1. story
2. reservation

```Далия``` 
1.ourDishes
2.ourMenu

```Игорь```
1. guests
2. gallery
3. footer 
насчет footer его нужно придумать исользуя стили сайта опираясь на его цвета шрифты и так далее
думаю над дизайном footera можно поработать всем 
накидать идей и мыслей

```Асема```
1.cookers
2. restaurant



```Название блоков:```
 1. header menu
 2. section logo
 3. section logoCards
 4. section story
 5. section reservation
 6. section ourDishes
 7. section ourMenu
 8. section guests
 9. section gallery
 10. section cookers
 11. section restaurant
 12. footer 


План нашего проекта:

1. Сверстать этот макет с помощью реакта 

2 в блоке menu есть кнопка «заказ столика »
Мы ее переименуем в «заказать блюдо»
При нажатии выходит окно
С инпутом и списком блюд 
Можно добавить маленькие картинки блюд цену ну и стилизовать красиво 
Самое главно в инпуте должна быть фильтрация 

3. В блоке guests мы используем api https://jsonplaceholder.typicode.com/comments
Не обязательно чтобы был посетитель и красивое описание 
Можно просто добавить описание самое главное мне кажется Эркутбек хочет чтобы мы научились работать с api и запросами
 
4. В блоке gallery также 
можно использовать api с https://jsonplaceholder.typicode.com/photos
Повторюсь мне кажется Эркутбек хочет чтобы мы научились использовать api 

5. Самим создать footer так как в макете его нет
Опираясь на цвета самого сайта и проявить немного фантазии



Дедлайн до 05.07.23



Давайте пока сделаем верстку 

Затем логику 

Можно потом еще подумать какую логику к чему и где можно добавить

А в конце уже палировка какими нибудь фишками сайта 
Стилями поиграться 
Логикой native js

жду идеи по поводу доработки проекта

или же предлогаю то что мы обсуждали 
1.сделать оставление отзывов
2.добавить блок наград ресторана
(у кого есть еще идеи предлагайте!)


и да кстати неплохо было бы придумать название для нашего ресторана 
есть идеи?
У меня была идейка типо ALEMOND 
незнаю почему просто прикольно 😂

‼️‼️‼️‼️‼️‼️
