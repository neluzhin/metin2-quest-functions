# pc.give_exp_perc()
Функция **pc.give_exp_perc** дает игроку количество опыта в процентах относительно определенного уровня и только один раз.

## Параметры функции
### flag_name
Тип *string*. **Обязательный параметр**. Имя флага, который будет создан (подробнее тут: [pc.give_exp](../pc/pc.give_exp.md)(); смысл этого параметра у этих функций одинаков).

### level
Тип *number*. **Обязательный параметр**. Уровень, относительно которого вы хотите дать опыт. Допустим, для поднятия второго уровня надо всего 800 единиц опыта, поэтому если вы третьим параметром укажете `20`, а вторым &mdash; `1`, то игроку дадут 20% опыта от второго уровня (160 единиц).

### exp_percentage
Тип *number*. **Обязательный параметр**. Количество процентов опыта относительно указанного во втором параметре уровня.

## Примечания
Функция **не** может быть вызвана анонимно.

Эту функцию лучше не использовать из-за поведения первого параметра. Лучше потратьте время и напишите собстенную функцию.