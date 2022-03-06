# Union.
**Задача 1:**                     
Да се създаде структура WeatherCast, която бива дефинирана спрямо           
температурата(TemperatureData) или вятъра(WeatherData).            

**Характеристики:**                  
TemperatureData             
- StationID (естествено число)          
- DayOfWeek               
- Температура в момента              
- Максимална температурата             
- Минимална температура             
                
WeatherData                 
- StationID (естествено число)             
- DayOfWeek                
- Speed (реално число)             
- Direction(North/South/West/East etc)                   
               
Да се напише програма, която проверява дали дадения WeatherCast е благоприятен,             
като ще го считаме за благоприятен ако:            
- Температурата е поне 15 градуса, като минималната не е под 10, а максималната над 27              
- Скоростта на вятъра е не по-голяма от 5км/ч.                             
              
# Файлове (част 1). Текстови файлове.

**Задача 2:**                             
От стандартния вход се прочитат три числа. Запишете във файл "result.txt"сумата и произведението им.                    
Направете функция, която извежда на стандартния изход разликата на сумата и произведението, прочетени от файла "result.txt".                          
Коректността на данните във файла, който четете, е гарантирана.                       

**Задача 3:**                                               
Да се напише подходящо параметризирана функция lengthOfFile(...) която връща колко символа има в текстов файл.                           
                           
**Задача 4:**                              
Да се създаде структура pair, която представя наредена двойка от естествени числа.                                  
Да се създаде структура, която представя релация. В релацията има най - много 25 наредени двойки и структурата пази текущия си размер.                    
Да се създаде функция writeRelationToFile(...), която записва релацията във файл с име "relation.txt"и readRelationFromFile(...), която чете релацията от файла.                 
Следните функции ще ви бъдат полезни:                   

- reatePair()             
- initPair()        
- readPairFromFile()                   
- writePairToFile()                       
- addPairToRelation()                                  
                   
Помислете какво трябва да приемат и връщат горните функции.                 
Напишете проста рограма, която демонстрира работата на написаната от вас програма.              
Ако решите максималният брой наредени двойки да стане 35, какво бихте направили?                       
                         
**Какво е сериализация и десериализация:**                                     
Сериализацията е процес на преобразуване на някаква структура от данни в поток от байтове.             
Потока може да бъде двоичен или текстов. Когато байтовете биват прочетени отново, чрез процеса на десериализацията, се създаваидентичнокопие на тази структура.              