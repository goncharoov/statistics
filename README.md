## Счетчики покрытия кода JaCoCo
JaCoCo использует несколько счетчиков для расчета показателей покрытия. Для ознакомления были изучены:
### INSTRUCTION
Метрика, предоставляющая информацию о том какое количество инструкций байт-кода было выполнено или пропущено.

### BRANCH
Метрика подсчитывающая общее количество ветвлений if и switch и определяющая количество выполненных или пропущеных веток.
Для оценки используются 3 возможных состояния:
1. Нет покрытия: не было выполнено ни одной ветки (красный ромб)
2. Частичное покрытие: была выполнена только часть ветвления (желтый ромб)
3. Полный охват: все ветви были выполнены (зеленый ромб)

### LINE
Для всех скомпилированных файлов классов можно рассчитать покрытие для отдельных строк. Строка считается выполненной, 
если выполнена хотя бы одна инструкция в ней. Предусмотрено три состояния:
1. Нет покрытия: в строке не было выполнено никаких инструкций (красный фон)
2. Частичное покрытие: была выполнена только часть инструкции в строке (желтый фон)
3. Полный охват: все инструкции в строке были выполнены (зеленый фон) 

