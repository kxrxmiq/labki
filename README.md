Новиков Кирилл Александрович 210901.
https://kxrxmiq.github.io/labki/
# CV
## Личная информация

|![](https://github.com/kxrxmiq/labki/blob/main/Я%201.jpg)|◦ ФИО: Новиков Кирилл Александрович <br> ◦ Дата рождения: 01.04.2005 <br> ◦ Группа: 210901 <br> ◦ GitHub: [kxrxmiq](https://kxrxmiq.github.io/labki/ "Перейти по ссылке") <br> ◦ Gmail: qwerty1122k@gmail.com <br> ◦ Deploy: [https://kxrxmiq.github.io/labki/](https://kxrxmiq.github.io/labki/ "Перейти по ссылке")|
|:---|:---|

## О себе
Я студент факультета компьютерного проектирования БГУИР, специальность ИПОИТ. В разработке основное внимание уделяю Java и всему, что с ней связано. Мне нравится, как Java сочетает простоту синтаксиса с мощными возможностями — от веб-разработки до анализа данных и автоматизации. Особенно увлекаюсь работой с Java Spring — ценю его гибкость и удобство при создании приложений.

Также исследую асинхронное программирование с помощью CompletableFuture в Java, что позволяет создавать высоконагруженные приложения. В планах — углубленное освоение Machine Learning с библиотеками, такими как Deeplearning4j и Weka, для решения сложных аналитических задач.

Люблю решать алгоритмические задачи и оптимизировать код, делая его более чистым и эффективным. Быстро обучаюсь новым технологиям и стараюсь сразу применять знания на практике. Хочу развиваться в направлении backend-разработки и Data Engineering, участвуя в проектах, где можно расти как специалист. Готов к сложным задачам, работе в команде и постоянному профессиональному развити

## Навыки
### *HardSkills*
+ **Языки программирования:** Java, JavaScript, Python, HTML, CSS
+ **Фреймворки и библиотеки:** Django, FastAPI, React,SpringBoot, Weka, Deeplearning4j
+ **СУБД:** PostgreSQL, MySQL
+ **Инструменты проектирования:** IntelliJ IDEA, PyCharm, Draw.io, Figma 
+ **Технологии:** Git, Docker 
+ **Методологии:** Wireframes, User stories, Empathy maps, User persona

### *SoftSkills*
+ Коммуникабельность
+ Работа в команде
+ Ответственность
+ Самообучаемость
+ Критическое мышление 
+ Адаптивность 
+ Эмпатия
+ Инициативность
+ Стрессоустойчивость
+ Креативность
+ Лидерские качества
+ Гибкость мышления

 ## Пример кода
 ```python
def bubble_sort(arr):
    n = len(arr)
    
    # Проходим по массиву n-1 раз
    for i in range(n - 1):
        # Флаг для оптимизации: если за проход не было обменов, массив уже отсортирован
        swapped = False
        
        # Внутренний цикл для сравнения соседних элементов
        for j in range(n - 1 - i):  # На каждом шаге наибольший элемент "всплывает" в конец
            if arr[j] > arr[j + 1]:  # Если текущий элемент больше следующего
                # Обмен элементов через кортежное присваивание
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
                swapped = True  # Фиксируем факт обмена
        
        # Ранний выход при отсутствии обменов
        if not swapped:
            break
    
    return arr

# Пример использования
if __name__ == "__main__":
    numbers = [64, 34, 25, 12, 22, 11, 90]
    print(f"Исходный массив: {numbers}")
    sorted_numbers = bubble_sort(numbers.copy())
    print(f"Отсортированный массив: {sorted_numbers}")
```

## Проекты
|№|Название|Период|Роль, функции <br> в проекте|Предметная область|
|:---:|:---:|:---:|:---:|:---:|
|1|Веб-приложение <br> для магазина одежды |Осень 2023|Курсовой проект|Backend, frontend, проектная аналитика|
|2|Автоматизированная система <br> учета в банке <br> |Весна 2023|Курсовой проект|Backend, frontend, <br> проектная аналитика|
|3|Веб-приложение <br> клуба настольных игр |Осень 2024|Курсовой проект|Backend, frontend, <br> проектная аналитика|

## Дополнительная информация
+ **Языки:** Владею английским на уровне С4. 
+ **Увлечения:**
  - Гребля
  - Футбол
  - Борьба
  - Гонки
  - Дота (7000 рейтинг)
  - Клеш рояль
  - Скалалазание
  - Триатлон
  - Профессиональное прокрастинирование
    
## Образование
|Период обучения|Название <br> учреждения <br> образования|Факультет|Специальность, <br> специализация|Средний <br> балл <br> последней <br> сессии|Форма обучения|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2022-2026|Белорусский <br> государственный <br> университет <br> информатики и <br> радиоэлектроники|Факультет <br> компьютерного <br> проектирования |Инженерно <br> психологическое <br> обеспечение <br> информационных <br> технологий, <br> инженер-системотехник|хватает|Очная|
