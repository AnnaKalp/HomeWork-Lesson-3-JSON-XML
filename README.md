## HomeWork-Lesson-3-JSON-XML
### Задача №1: проверить XML на Well formed:

<req>

        <surname>Иванов</surname>

        <name>Иван</name>

        <patronymic>Иванович</patronymic>

        <birthdate>01.01.1990</birthdate>

        <birthplace>Москва</birthplace>

        <phone>8 926 766 48 48</phone>

</req>

Ответ: Well formed(правильно)


**Задача №2:** проверить JSON на Well formed:

```json
{

        ""surname"": ""Иванов""

        ""name"": ""Иван""

        ""patronymic"": ""Иванович""

        ""birthdate"": ""01.01.1990""

        ""birthplace"": ""Москва""

        ""phone"": ""8 926 766 48 48""

}
</aside>

Ответ: not Well formed(неправильно, исправила). Массив должен быть заключён в [] - скобки, а объекты в ней в {} - скобки. Нужно убрать парные ковычки и поставить запятые в конце каждой строки, кроме последней.

[
  {

        "surname": "Иванов",

        "name": "Иван",

        "patronymic": "Иванович",

        "birthdate": "01.01.1990",

        "birthplace": "Москва",

        "phone": "8 926 766 48 48"

   }
]
