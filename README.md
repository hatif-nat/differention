## Дифференцирование математического выражение
Входные данные программы имеют вид Dпеременная: выражение
После буквы D указывается имя переменной дифференцирования, а после двоеточия – дифференцируемое выражение
Синтаксис дифференцируемого выражения описывается с помощью следующих БНФ-правил:
выражение  ::=  слагаемое  |  выражение  знак_суммирования   слагаемое
знак_суммирования  ::=   +  |  –
слагаемое  ::=  множитель  |  слагаемое  знак_умножения   множитель
знак_умножения  ::=   *  |  /
множитель  ::=  целое_без_знака   |   переменная   |   переменная^степень
	|   имя_функции(выражение)   |   (выражение)   | 
 		 (выражение)^степень
переменная  ::=  идентификатор
степень  ::=  знак   целое_без_знака
знак  ::=   пусто  |  +  |  –
имя_функции  ::=  sin | cos | ln | exp | sqrt | 	
             arcsin | arccos
