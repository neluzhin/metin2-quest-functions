# sys_err()
Функция **sys_err** записывает определенную ошибку в файл `syserr`.

## Параметры функции
### error_msg
Тип *string*. **Обязательный параметр**. Сообщение об ошибке.

## Примечания
Функция **не** может быть вызвана анонимно.

Запись будет иметь следующий вид: `QUEST: quest: {quest_name} player: {player_name} : {error_msg}`, где `{quest_name}` &mdash; имя квеста, в котором была вызвана функция; `{player_name}` &mdash; имя игрока, который вызвал функцию; `{error_msg}` &mdash; значение параметра [error_msg](#error_msg).

Также игрок увидит в чате сообщение `QUEST_SYSERR {error_msg}`.

Файл `syserr` находится в папке конфигурации каналов. Запись будет совершена только в один `syserr`; в тот, что находится в той же папке, которая соответствует каналу или подканалу игрока.