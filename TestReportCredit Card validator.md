## Отчёт о тестировании Credit Card Number Validator
***
### Краткое описание

25.10.2020 – 26.10.2020  было проведено функциональное тестирование приложения _Credit Card Number Validator_

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [Credit Card Number Validator не распознает валидные номера карт Union Pay](https://github.com/YuliaKulini4/Kulinich-git19-2-3/issues/3#issue-729907608)
* [Credit Card Number Validator не распознает валидные номера карт Diners Club – International](https://github.com/YuliaKulini4/Kulinich-git19-2-3/issues/2#issue-729886699)
* [Credit Card Number Validator не распознает валидные номера American Express ](https://github.com/YuliaKulini4/Kulinich-git19-2-3/issues/1#issue-729879442)

### Описание процесса тестирования

В процессе тестирования использовался:

[Tест кейс](https://github.com/YuliaKulini4/Kulinich-git19-2-3/issues/4#issue-729939654)


В качестве тестовых данных использовались данные сгенерированные на  www.freeformatter.com

|  Номер карты |   Вид карты |  Ожидаемый результат
|-----------------------|------|-----------------------|
|  4539067186269917    |   VISA|  Result is OK|
| 	4508297343552874   |   Visa Electron | Result is OK|
| 	5204026723141725  |   MasterCard | Result is OK   |
| 	370881301792367  |      American Express (AMEX)| Result is OK
| 	0604224809921964   |   Maestro|  Result is OK |
| 	2201382000000013   |     МИР|  Result is OK |
|  	3569219489416316   |  JBC|  Result is OK |
| 	36516332652711    |      Diners Club – International|  Result is OK |
| 	6011773402664540   |   Discover|  Result is OK |
|	6213900936908920  |  Union Pay | Result is OK |


### _Тестирование производилось в следующем окружении:_

•	Windows 10 Pro /1903 / 64-bit,

•	JDK 11.0.9_11,

•	InteliJ IDEA 2020.2.3


