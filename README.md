## Дифференцирование математического выражение
Входные данные программы имеют вид Dпеременная: выражение, после буквы D указывается имя переменной дифференцирования, а после двоеточия – дифференцируемое выражение, например: 
Dy:sin(x+2*y)*y^-4+(8*a-b)*sqrt(sin(y-2)+cos(y+9))
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
