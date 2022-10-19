# Построение графа друзей VK

Задание выполнено в рамках курса "Интеллектуальные системы и технологии"

## Задачи
1. Построить граф друзей VK
2. Оценить центральность графа: по посредничеству, по близости, собственного вектора

## Результат
*Примечание: в этом разделе показан результат с ограничением количества друзей = 5. При выборке в 200 друзей время работы программы составляет более двух часов*

### Изображение графа

### Результат
```python
Requirement already satisfied: vk_api in /usr/local/lib/python3.7/dist-packages (11.9.9)
Requirement already satisfied: requests in /usr/local/lib/python3.7/dist-packages (from vk_api) (2.23.0)
Requirement already satisfied: certifi>=2017.4.17 in /usr/local/lib/python3.7/dist-packages (from requests->vk_api) (2022.9.24)
Requirement already satisfied: chardet<4,>=3.0.2 in /usr/local/lib/python3.7/dist-packages (from requests->vk_api) (3.0.4)
Requirement already satisfied: urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 in /usr/local/lib/python3.7/dist-packages (from requests->vk_api) (1.24.3)
Requirement already satisfied: idna<3,>=2.5 in /usr/local/lib/python3.7/dist-packages (from requests->vk_api) (2.10)
user 155422882 is deleted
user 214554287 is deleted
user 216980163 is deleted
user 232140912 is deleted
user 268384509 is deleted
user 271389258 is deleted
user 287349802 is deleted
user 293853610 is deleted
user 437846556 is deleted
user 454405130 is deleted
user 499619589 is deleted
user 515292000 is deleted
user 528201638 is deleted
Близостная центральность:
(208131632, 0.5012485363204153)
```
