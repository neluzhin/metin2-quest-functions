# forked.getdeadcount()
Функция **forked.getdeadcount** сообщает, сколько раз может умереть игрок во время битвы империй.

## Возвращаемые значения
### dead_count
Тип *number*. Число, означающее, сколько ещё раз может умереть игрок. Если функция была вызвана вне битвы империй, то возвращается `0`.

## Примечания
Функция **не** может быть вызвана анонимно.

Данная функция работает только во время битвы империй (см. [forked](../forked)).