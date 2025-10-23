# sql_hometask2_LazukinaVA
**1. ERD - Система интерактивного обучения**
Архитектура БД построена с учетом 3-й нормальной формы. Во избежание связи many-to-many была создана связующая таблица между таблицами Students и Streams. 

Изначально была создана предварительная схема

![Предварительная схема](https://github.com/user-attachments/assets/054d1b3c-11e5-4886-9def-29e2bc1c69a0)

После чего создана БД

![ДИАГРАММА СИСТЕМА ИНТЕРАКТИВНОГО ОБУЧЕНИЯ](https://github.com/user-attachments/assets/21eb2676-4b30-4167-ab74-8543b7ee1500)

**2. Запросы на создание таблиц**
*CREATE TABLE / CONSTRAINT / PR/ FOREIGN KEY*

![запросы_создание_таблиц_1](https://github.com/user-attachments/assets/7e8b769d-d782-4e1b-9daa-50b8fa6af7f7)
![запросы_создание_таблиц_2](https://github.com/user-attachments/assets/d7f97684-b344-4808-874a-a7533910937e)
![запросы_создание_таблиц_3](https://github.com/user-attachments/assets/7927ccd9-da41-4949-ba50-2c7bbff63acb)

**3. Заполнение таблиц**
*INSERT INTO / ALTER TABLE/ UPDATE*

![заполнение_данных_1](https://github.com/user-attachments/assets/f2bc3e69-70f6-4b88-9749-901af82e8845)
![заполнение_данных_2](https://github.com/user-attachments/assets/bfd9b889-7563-4c67-bb1d-74fd09e10cd0)
![заполнение_данных_3](https://github.com/user-attachments/assets/12a60b10-145d-46c6-a293-c4ee294270bd)
![заполнение_обновление_данных__4](https://github.com/user-attachments/assets/b19571fe-362d-4bcf-b24e-c38cd5378ce6)

**4. Выборка данных**
*DML/ CTE/ оконные функции/ JOIN/ оператор CASE/ UNION*
Запрос с UNION и CTE
![Запрос с UNION и СTE](https://github.com/user-attachments/assets/f0720004-5027-4e5d-b950-0731c5e61646)
![Агрегация, join, case_when](https://github.com/user-attachments/assets/26f5b509-6fd7-41c4-87c2-b43733651499)
![over_join](https://github.com/user-attachments/assets/7a2bfbdc-cef5-44b7-b561-99d592fe3c46)
![Join_LIKE](https://github.com/user-attachments/assets/614b5318-b06b-4eda-a4ac-1770a36edf54)
![join и where (between)](https://github.com/user-attachments/assets/5a672a55-6a84-4a48-8b08-6de74977160c)
