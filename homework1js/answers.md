## Теоретические вопросы
1. Обьяснить своими словами разницу между обьявлением переменных через var, let и const. 
2. Почему объявлять переменную через var считается плохим тоном?

## Ответы
1. **let** переменная может менять значения в последствии     
const переменную нельзя изменить в будущем, при выборе,  
стараемся использовать по возможности **const**,  
к **let** и **const** нельзя обратится до их объявления,  
var видно всегда, даже если она ниже в коде,  
**let** и **const** имеют блочную вивдимость и после фигурных скобок возвращается к значению перед ними  
var продолжает выполняться за пределами фигурных скобок это не всегда удобно  
        
1. **var** больше вероятность возникновения ошибок в коде из-за ее видимости  
за пределами фигурных скобок,  
let и const – основной способ объявления переменных,  
рекомендованый в новом стандарте **es6**.