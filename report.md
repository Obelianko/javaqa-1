Отчёт о тестировании Credit Card Number Validator
Краткое описание
21/05/21-21/05/21  было проведена проверка валидации кредитных карт приложения Credit Card Number Validator.

На тестирование затрачен 1 час

В результате тестирования выявлены следующие дефекты:

https://github.com/Obelianko/javaqa-1/issues/3
https://github.com/Obelianko/javaqa-1/issues/2
https://github.com/Obelianko/javaqa-1/issues/1
Описание процесса тестирования
Тестирование проводилось с использованием IntelljIdea

В качестве тестовых данных использовались данные карт сгенерерованные на следующих ресурсах: https://fakepersongenerator.com/credit-card-generator; https://creditcardgenerator.in/bulk-credit-card-generator
Карты платежной системы MAstercard:
5494306258377954-test OK
5305419856427920-test ok
5496811632080792-test ok
5494449858011472-test ok
Карты платежной системы VISA:
4509863750940271-test ok
4509863750940271-test ok
4048232340943674-test ok
4536586989547248-test ok
Карты платежной системы AMEX
372877998282272 test ok
378699910852642 test ok
341675099012798 test ok
348550438171675 test ok
Карты платежной системы MIR
2203237421559181 test ok
2204024166692470 test ok
2224546776885775 test ok
Карты платежной системы Discover
6011315630689178 test ok
6011634985046440 test ok
6587525549036147 test ok
6011613791774064 test ok
Карты платежной системы JCB
3528264849401772 test ok
3588608011319088 test ok
3569893277799917 test ok
3558444197290869 test ok
Карты платежной системы Diners club
38530977219858 test ok
36781931725058 test ok
38311290788253 test ok
5991706068000761 test ok
38964965753661 test ok 
5737015887801170 test ok

Тестирование производилось в следующем окружении:

OC X El Capitan 10.11.6 (15G22010)
openjdk 11.0.10 2021-01-19
IntellijIDEA 2021.1.1

