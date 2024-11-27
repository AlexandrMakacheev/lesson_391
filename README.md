1. Публикуем наш проект на GitHub:
- вкладка VSC -> Share Project on GitHub.
2. Ситуация: нам пришла какая-то задача на выполнение. Домашнее зажание. Наши действия:
- создаем ветку в которой будем вести разработку(вкладка слева снизу Version Control).
- ведем разработку и решаем задачу находясь в созданной ветке.
- делаем Commit. Commit - это фиксация (сохранение) на локальном компьютере состояния программы с учетом сделанных
изменений. Вкладка Commit (слева).
- делаем push. Push - это выгрузка в удаленный репозиторий всех сделанных коммитов. Зеленая стрелка справа сверху.
- переходим на GitHub и создаем там Pull Request.
- созданный Pull Request проверяется (преподавателем, старшим разработчиком).
- после проверки осуществляется операция Merge Pull Request -  запрос на слияние веток удовлетворяется. Во время
этого запроса процесса кодиз ветки, в которой велась разработка, попадает в ветку master.
- после этого ненужная более ветка удаляется.
- На локальной машине мы обновляем состояние ветки master и тоже удаляем другую более не нужную ветку.