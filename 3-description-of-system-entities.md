# 3. ОПИСАНИЕ СУЩНОСТЕЙ СИСТЕМЫ
## 3.1.	Сущности предметной области "Формирование отчета"
### 3.1.1.	Логическая схема предметной области "Формирование отчета"  

![Рисунок 1](./Логическая_схема.png)

Рисунок 1 – Логическая схема предметной области "Формирование отчета"

Таблица 1 – Описание атрибутов сущности предметной области 1
| № п/п | Атрибут | Обязательность | Тип данных |
|----|----|----|----|
| 1 | user_id  |  yes | integer |
| 2 |  user_name | yes  | character vary  |
| 3 |  email | yes  |  character vary  |
| 4 |  password | yes  |  character vary  |
| 5 |  number | yes  | character vary   |
| 6 |  notification |  yes |  character vary  |
| 7 |  documents_id |  yes |  integer |
| 8 |  foto | yes  | bytea  |
| 9 |  ofd |  yes | bytea  |
| 10 |  report_id | yes  |  integer |
| 11 |  сhild's_name | yes  |  character vary  |
| 12 |  text | yes  |  character vary  |
| 13 |  stasus | no  |  character vary  |
| 14 |  comments |  no |  character vary  |
| 15 |  employee_name |  yes |  character vary  |
| 16 |  created_at |  yes |  date  |
| 17 |  apdated_at |  yes |  date  |

###3.1.2.	Физическая модель данных предметной области 1  

![Рисунок 1](./БД.png)  
Рисунок 1 – Физическая модель данных предметной области "Формирование отчета"

Таблица 2 – Описание атрибутов таблицы БД предметной области 1
| № п/п | Атрибут | Наименование в БД | Обязательность | Тип данных в БД и длина | Комментарии, правила валидации |
|----|----|----|----|----|----|
| 1 |   |   |  | *[Типы данных char, int, float, date и т.д.]* |  |
| 2 |   |   |   |   |   |
| 3 |   |   |   |   |   |
| 1 | user_id  |  yes | integer |
| 2 |  user_name | yes  | character vary  |
| 3 |  email | yes  |  character vary  |
| 4 |  password | yes  |  character vary  |
| 5 |  number | yes  | character vary   |
| 6 |  notification |  yes |  character vary  |
| 7 |  documents_id |  yes |  integer |
| 8 |  foto | yes  | bytea  |
| 9 |  ofd |  yes | bytea  |
| 10 |  report_id | yes  |  integer |
| 11 |  сhild's_name | yes  |  character vary  |
| 12 |  text | yes  |  character vary  |
| 13 |  stasus | no  |  character vary  |
| 14 |  comments |  no |  character vary  |
| 15 |  employee_name |  yes |  character vary  |
| 16 |  created_at |  yes |  date  |
| 17 |  apdated_at |  yes |  date  |

### 3.1.3.	SQL-запрос для предметной области 1
*[Необходимо написать SQL-запрос, который воссоздаст фрагмент БД по приведенной выше физической модели данных. Каждую таблицу следует наполнить минимум тремя записями.]*
