[Мой Чемпион](https://github.com/AndreySysa/My_champion/blob/main/Мой%20чемпион.ipynb)[^1]
***
Заказчик

Компания GoProtect
***
Описание проекта

Сервис  “Мой Чемпион” помогает спортивным школам фигурного катания, тренерам мониторить результаты своих подопечных и планировать дальнейшее развитие спортсменов.
***
Цель
Создать модель, помогающую находить элементы, которые могут быть успешно исполнены спортсменом на соревновании. 
Сервис будет прогнозировать прогресс и возможное выполнение тех или иных элементов программы по истории предыдущих выступлений и выполнения элементов на соревнованиях.
Задачи DS 

 - Объединить данные – спортсмены, юниты, соревнования, сегменты, школы, тренеры
 - Провести анализ данных, изучить аномалии, корреляции, описать наблюдения и сделать выводы
 - Выделить все элементы фигурного катания, представленых в виде объединенной строки с набором элементов например 2F!<<+2Lo<<CCoSp2V*
 - Актуальный список элементов можно посмотреть здесь https://eislauf-union.de/files/users/997/Elemente-Liste2023_24.pdf вам нужна будет только категория Single skating, а также специальные отметки Special codes в конце документа
 - Выделить элементы успешно выполненные и с погрешностями (имеют специальные пометки)
 - Агрегировать датасет и подготовить обучающие признаки
 - Создать модель для предсказания вероятности успешного выполнения элементов
 - Проанализировать признаки, выявить ошибки и слабые стороны модели, улучшить решение
 - Создать функцию (класс) для применения в сервисе
 - возможность регулировки длины истории спортсмена для построения прогноза, например использовать последние N соревнований (выбор модели или запуск обучения)
 - добавление запланированной программы элементов в качестве признака
 - Протестировать решение
 - Создать документацию
 - описание признаков
 - какая модель используется
 - как оценивается качество
 - инструкция по запуску (применению)
 - Готовый проект предоставить в виде репозитория на гитхабе
 - * предложить свои варианты оценки успешности выступления
 - * оформить в виде приложения, используя библиотеку Streamlit или подобную


[^1]:Для корректного просмотра Jupyter notebook с работающим содержанием, пожалуйста, используйте следующую ссылку:
[Мой Чемпион](https://nbviewer.jupyter.org/github/AndreySysa/My_champion/blob/main/Мой%20чемпион.ipynb)
Просто кликните на ссылку, и nbviewer отобразит notebook с интерактивными ссылками.

