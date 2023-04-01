### Lesson 12 - Lists: slices and comparision [13]
- Reference: https://www.youtube.com/watch?v=Vx3s01Yb1P8
- Play with lists: slices and comparision [13]
  - ___meta_: 
    - [?] Maybe it is better to cover methods of lists because boolean operations might not be covered before the lesson.
    - Anyway, it is good to have this lesson short and simple to avoid confusion and overwhelming by the end of the course.
- H/w:
  - 46\. Що напечатає дана програма:
    ```
    l = [1, 2, 3, 4, 5]
    print(l[1:3])

    ```
    - Radio buttons:
      - [1, 2, 3]
      - [1, 2]
      - [2, 3, 4]
      - [2, 3]
  - 47\. Програма отримує рядок з назвами міст, розділених пробілами. Напишіть код, який виводить міста через один, починаючи з 0-го.
     - Доповніть код:
      ```
       cities = input().split()
   
       # your code here
       ```
  - 48\. Програма отримує рядок з балами студента розділених пробілом. Треба роздрукувати бали з 5 по 8 включно в зворотньому порядку.
     - Доповніть код:
      ```
       marks = list(map(int, input().split()))
   
       # your code here
       ```
  - 49\. Програма отримує рядок з балами студента розділених пробілом. Бали в диапазоні від 5 до 12. Потрібно роздрукувати скількі разів студент отримав максимальний бал 12.
     - Доповніть код:
      ```
       marks = list(map(int, input().split()))
   
       # your code here
       ```
  - 50\. Програма отримує рядок з повним ім'ям студента: ім'я, по-батькові, прізвище. Потрібно вивести ім'я у виді: Прізвище І. П.
     - Доповніть код:
      ```
       s = input("Введіть повне ім'я: ")
   
       # your code here
       ```