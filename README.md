# gitflow-example
hahaha
1. создаем репозиторий на github
2. клонируем его к себе на компьютер
3. создать ветку разработки от основной ветки
4. после из ветки разработки создаются отдельные ветки в которых мы реализуем отдельные "фичи"
5. после реализации какой-либо "фичи" мы мержим ветку в которой мы реализовали данную "фичу" в ветку разработки 
6. создание ветки release/0.1.0 от ветки разработки
7. после того как ветка release/0.1.0 завершена она мержится в main и develop и затем удаляется
8. если в ветке main обнаруживается ошибка то от ветки main создаётся ветка hotfix - ветка для исправления ошибок
9. после того как работа над веткой hotfix завершена, она мержится в develop и main
10. после того как смержили ветку hotfix вуетка удаляется.